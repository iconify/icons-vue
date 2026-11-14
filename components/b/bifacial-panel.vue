<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6th0gjqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bifacial-panel" /></template>
<style>
.y6th0gjqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.392 12.451l7.782-5.449a1.25 1.25 0 0 1 1.741.307a1.25 1.25 0 0 1-.307 1.74l-7.782 5.449a1.25 1.25 0 0 1-1.741-.307a1.25 1.25 0 0 1 .307-1.74M12 12.25v8.25m-3 0h6M4 4l4.5 4.5m-3 0h3v-3m12 11.5l-4-4m0 3v-3h3");
}

</style>
