<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ag4mw07mm"/><path class="p6n_bt1rh"/><path class="b_c3q5dqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contract-renewal" /></template>
<style>
.ag4mw07mm {
  d: path("m17.601 4.631l1.768 1.768l-6.717 6.717L10 14l.884-2.652Z");
}

.b_c3q5dqf {
  d: path("M7.5 7.5L9.25 9l-1.5 1.75");
}

.p6n_bt1rh {
  d: path("M14.924 14.868a5 5 0 1 1-5.792-5.792");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
