<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4cob6b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4cob6b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:divide" /></template>
