<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lzwmybcae"/><path class="hummh5bex"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crypto-calculator" /></template>
<style>
.hummh5bex {
  d: path("M6.5 5.5H12V9H6.5Zm0 7.5h.01m2.74 0h.01M12 13h.01M6.5 17h.01m2.74 0h.01M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.lzwmybcae {
  d: path("M12.4 21.5H3.5v-19H15v9.7");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
