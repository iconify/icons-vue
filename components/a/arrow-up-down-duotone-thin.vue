<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wj8ybccjk"/><path class="bztdq0bdr"/><path class="ifr8xwb3y"/><path class="r7xk8o29f"/><path class="h3z-uye4u"/><path class="qrnoe1--b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-up-down-duotone-thin" /></template>
<style>
.bztdq0bdr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 8 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h3z-uye4u {
  d: path("m8 8 4 -4 4 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ifr8xwb3y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 16 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qrnoe1--b {
  d: path("m8 16 4 4 4 -4");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.wj8ybccjk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
