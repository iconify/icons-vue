<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xn-wbelon"/><path class="beuio438u"/><path class="jkskk7b5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carpet-shop" /></template>
<style>
.beuio438u {
  d: path("M5.5 2.5h15a1.5 3 0 0 1 0 6m-15 0v10h15v-10m-15-3h.01");
}

.jkskk7b5y {
  d: path("m13 11.25l2.25 2.25L13 15.75l-2.25-2.25ZM8.5 18.5V21m3-2.5V21m3-2.5V21m3-2.5V21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xn-wbelon {
  d: path("M2.5 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
