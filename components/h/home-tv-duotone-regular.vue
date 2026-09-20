<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r39poztgk"/><path class="mjfvqdb6k"/><path class="pa9quik2g"/><path class="jwnes9bsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-tv-duotone-regular" /></template>
<style>
.jwnes9bsk {
  d: path("M8 19h8");
}

.mjfvqdb6k {
  d: path("M3 5v11h18V5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pa9quik2g {
  d: path("M12 16v3");
}

.r39poztgk {
  fill: currentColor;
  d: path("M3 5v11h18V5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
