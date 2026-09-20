<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rw52-bbtm"/><path class="f6tip2cru"/><path class="p6nkr755w"/><path class="hq3guo9pr"/><path class="f1p3_92ft"/><path class="hd8_4bbku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-candlestick-outline-thin" /></template>
<style>
.f1p3_92ft {
  d: path("M12.5 11a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.f6tip2cru {
  d: path("M2.5 10a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.hd8_4bbku {
  d: path("M16 16v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hq3guo9pr {
  d: path("M16 5v4");
}

.p6nkr755w {
  d: path("M6 16v4");
}

.rw52-bbtm {
  d: path("M6 4v4");
}

</style>
