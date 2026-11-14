<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzzpnkb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:firework-cake" /></template>
<style>
.mzzpnkb4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.625 13h10.75A2.625 2.625 0 0 1 20 15.625v3.25a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 18.875v-3.25A2.625 2.625 0 0 1 6.625 13m2.625 0v8.5m5.5-8.5v8.5M12 4.5V2.25M12 8v2.25m-1.75-4H8m5.75 0H16M10.75 5l-1.5-1.5m4 1.5l1.5-1.5m-4 4L9.25 9m4-1.5l1.5 1.5");
}

</style>
