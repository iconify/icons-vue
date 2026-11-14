<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x5lzab96o"/><path class="zt9xf1fig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:auto-injector" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x5lzab96o {
  d: path("m6.166 13.591l4.95-4.95a3 3 0 0 1 4.243 0a3 3 0 0 1 0 4.243l-4.95 4.95a3 3 0 0 1-4.243 0a3 3 0 0 1 0-4.243");
}

.zt9xf1fig {
  d: path("m15.094 6.255l.578-.238a1.5 1.5 0 0 1 1.631.326l.354.354a1.5 1.5 0 0 1 .326 1.631l-.238.578a1.083 1.083 0 0 1-1.768.354L14.74 8.023a1.083 1.083 0 0 1 .354-1.768m-8.221 6.629l4.243 4.243M17.48 6.52l2.298-2.298");
}

</style>
