<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty9vevbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty9vevbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:flash" /></template>
