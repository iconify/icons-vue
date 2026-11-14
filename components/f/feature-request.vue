<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckp39-bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:feature-request" /></template>
<style>
.ckp39-bef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 17.5V16c-2-1.2-3.25-3.1-3.25-5.5a6.25 6.25 0 0 1 12.5 0c0 2.4-1.25 4.3-3.25 5.5v1.5Zm.5 3.5h5M12 7.75v5.5M9.25 10.5h5.5");
}

</style>
