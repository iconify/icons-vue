<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eqkdskbqn"/><path class="ztj_ad7go"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deforestation" /></template>
<style>
.eqkdskbqn {
  d: path("M4 21.25q2.625-.75 3-3V11.5h10v6.75q.375 2.25 3 3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ztj_ad7go {
  d: path("M7 14.5c3 1.25 7 1.25 10 0m-7 3.25v1.75m1.53-11.53l.69-.69q.53-.53 1.15-.11l3.26 2.16q.62.42.09.95l-2.19 2.19q-.53.53-.95-.09l-2.16-3.26q-.42-.62.11-1.15m.22-.47L7.25 3");
}

</style>
