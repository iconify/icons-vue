<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z1xadabxd"/><path class="diexuobdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lip-reading" /></template>
<style>
.diexuobdh {
  d: path("M5.5 13.5c2.25.75 4.5 1 6.5 1s4.25-.25 6.5-1m-11-8.75c2.75-2.5 6.25-2.5 9 0c-2.75 2.5-6.25 2.5-9 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z1xadabxd {
  d: path("M2.75 13.5c3-3.5 6-4.5 9.25-2.75C15.25 9 18.25 10 21.25 13.5c-3 3.75-6 5.5-9.25 5.5s-6.25-1.75-9.25-5.5");
}

</style>
