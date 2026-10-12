<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ake-zzb7h"/><path class="pe4pc-o8q"/><circle class="i25ptdbyc"/><path class="wxuf-2f2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:key-exchange" /></template>
<style>
.ake-zzb7h {
  cx: 5.5px;
  cy: 6px;
  r: 2.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i25ptdbyc {
  cx: 18.5px;
  cy: 18px;
  r: 2.75px;
}

.pe4pc-o8q {
  d: path("M8.25 6H15m-2 0v2m6.25-4.5v5.75M17.5 7.5l1.75 1.75L21 7.5");
}

.wxuf-2f2u {
  d: path("M15.75 18H9m2 0v-2m-6.25 4.5v-5.75M3 16.5l1.75-1.75L6.5 16.5");
}

</style>
