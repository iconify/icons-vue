<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="klf5vzbha"/><path class="rwn_p9bfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:equipment-out-of-order" /></template>
<style>
.klf5vzbha {
  d: path("M3.5 21.5v-19h11V12M9 2.5V10");
}

.rwn_p9bfk {
  d: path("M6.5 10h5v6h-5ZM18 13.25l4 8.25h-8Zm0 5.25h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
