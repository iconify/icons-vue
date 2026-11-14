<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1w-sib5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-cashback" /></template>
<style>
.y1w-sib5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.845 18.655L12 19.5L4.5 12c-2-2-2-5.5.75-7c2.5-1.25 5.25-.5 6.75 2c1.5-2.5 4.25-3.25 6.75-2c2.319 1.265 2.682 3.952 1.54 5.962m-6.596 6.844l-.213.213m6.269-1.769C19.5 15.5 18.9 15 18 15c-1.05 0-1.75.6-1.75 1.5c0 1.6 3.5.9 3.5 3c0 .9-.75 1.5-1.75 1.5c-.9 0-1.55-.4-1.75-1M18 13.75V15m0 6v1");
}

</style>
