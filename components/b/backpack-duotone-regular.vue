<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="urfzt0bgl"/><path class="ls6sunbjf"/><path class="wlp3ibbib"/><path class="ky6vhkb9o"/><path class="q9rg3vk5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:backpack-duotone-regular" /></template>
<style>
.ky6vhkb9o {
  d: path("M9 2v2.5");
}

.ls6sunbjf {
  d: path("M6 21V9a6 6 0 0 1 12 0v12Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q9rg3vk5x {
  d: path("M15 2v2.5");
}

.urfzt0bgl {
  fill: currentColor;
  d: path("M6 21V9a6 6 0 0 1 12 0v12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wlp3ibbib {
  d: path("M6 13h12");
}

</style>
