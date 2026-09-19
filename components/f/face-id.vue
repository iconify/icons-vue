<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj5ftbbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj5ftbbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:face-id" /></template>
