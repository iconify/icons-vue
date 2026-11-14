<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jwxm5cc4m"/><path class="kl0lk4qlc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balise" /></template>
<style>
.jwxm5cc4m {
  d: path("M3 15h18v5H3Zm6.5-3.5a3.5 3.5 0 0 1 5 0m-7-2a6.5 6.5 0 0 1 9 0");
}

.kl0lk4qlc {
  d: path("M5.25 7.25a9.5 9.5 0 0 1 13.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
