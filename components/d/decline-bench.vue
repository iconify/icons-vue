<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r6r-sbclq"/><path class="yivntmbbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:decline-bench" /></template>
<style>
.r6r-sbclq {
  d: path("m2.5 12l19-6.5V9l-19 6.5Zm2 7.5H7V14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yivntmbbl {
  d: path("M14.5 19.5H17v-9m-10 9h2.5m7.5 0h2.5");
}

</style>
