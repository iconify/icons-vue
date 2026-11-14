<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d_u7w_bfn"/><path class="egla8wwbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:counterfeit-pen" /></template>
<style>
.d_u7w_bfn {
  d: path("M11.7 19H2.5V5h19v6.8");
}

.egla8wwbn {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-3 0h.01m8.24 9.75l.25-2.5L19.75 14L22 16.25l-5.25 5.25Zm3.5-5.75L20 18.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
