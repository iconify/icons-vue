<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wktrzo4kx"/><path class="jed1n_btf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contrail" /></template>
<style>
.jed1n_btf {
  d: path("M13.75 10.75Q7 13 3 20.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wktrzo4kx {
  d: path("m20.536 3.964l-.354 1.768L18.414 7.5l.707 4.243l-.707.707l-1.768-3.182l-1.414 1.414v2.121l-1.414-2.121l-2.121-1.414h2.121l1.414-1.414l-3.182-1.768l.707-.707L17 6.086l1.768-1.768Z");
}

</style>
