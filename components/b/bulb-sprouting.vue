<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr350de0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bulb-sprouting" /></template>
<style>
.xr350de0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.5c1 2.5 6.5 3.5 6.5 7.5c0 2.75-3 3.5-6.5 3.5s-6.5-.75-6.5-3.5c0-4 5.5-5 6.5-7.5m0 0v-5m0 3c0-2 2-3 4.5-3c0 2-2 3.25-4.5 3m-2.5 13L8.75 21M12 18.5v3m2.5-3l.75 2.5");
}

</style>
