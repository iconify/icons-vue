<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg4l5ub6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cruise-liner-sharp" /></template>
<style>
.dg4l5ub6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12.5v-3h3V6H17l.27.7l2.21 5.85l.27.7H5.5zm3-3h7.25m-3.58-3.99l-.34-2.27l-.08-.49h2.5l.08.49l.34 2.27l.08.49h-2.5zm-8.42 7.74h17.5l-.41.91l-1.18 2.68l-.41.91H4.75l-.41-.91l-1.18-2.68l-.41-.91zm3.5 2.25h.5m2.5 0h.5m2.5 0h.5m2.5 0h.5m-14 5.75c1.5 0 1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1");
}

</style>
