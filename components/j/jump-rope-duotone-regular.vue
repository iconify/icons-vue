<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="umge8xb0s"/><path class="fkvuv9bip"/><path class="kfoh62enz"/><path class="eguxbnz0i"/><path class="a3zqh3bcj"/><path class="he6b77rju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:jump-rope-duotone-regular" /></template>
<style>
.a3zqh3bcj {
  d: path("M2 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.eguxbnz0i {
  d: path("M20 10a8 8 0 0 1 -16 0");
}

.fkvuv9bip {
  fill: currentColor;
  d: path("M18 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.he6b77rju {
  d: path("M18 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.kfoh62enz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 10a8 8 0 0 1 -16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.umge8xb0s {
  fill: currentColor;
  d: path("M2 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
