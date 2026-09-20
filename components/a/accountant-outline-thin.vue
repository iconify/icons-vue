<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pemn838wn"/><path class="ia4sldbfw"/><path class="uftinba5h"/><path class="o3bdao7ob"/><path class="o62mcobgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:accountant-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ia4sldbfw {
  d: path("M3 21a9 9 0 0 1 18 0");
}

.o3bdao7ob {
  d: path("m9 20 6 -6");
}

.o62mcobgu {
  d: path("M13.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.pemn838wn {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.uftinba5h {
  d: path("M8.5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
