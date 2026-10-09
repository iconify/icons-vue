<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5wmwdblu.css';
import '../../css/k/kvqjz7b_z.css';
import '../../css/u/udpsv_2mb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r5wmwdblu"/><path class="kvqjz7b_z"/><path class="udpsv_2mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-clock-20-bold" /></template>
