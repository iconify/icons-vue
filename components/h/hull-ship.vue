<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w2qwahbyy"/><path class="u3a0crbwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hull-ship" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u3a0crbwd {
  d: path("M15 8.75a2.5 2.5 0 1 0 0 5a2.5 2.5 0 1 0 0-5m-3.5 2.5h7m-15.75 9.5C4 20.75 4 20 5.25 20s1.25.75 2.5.75S9 20 10.25 20s1.25.75 2.5.75S14 20 15.25 20s1.25.75 2.5.75S19 20 20.25 20");
}

.w2qwahbyy {
  d: path("M3.5 6h15q.75 0 1.12.65l1.26 2.2q.37.65.12 1.36l-2 5.58q-.25.71-1 .71H6.25q-.75 0-.94-.73L2.94 6.73Q2.75 6 3.5 6");
}

</style>
