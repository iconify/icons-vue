<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1izm_bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1izm_bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-day-line" /></template>
