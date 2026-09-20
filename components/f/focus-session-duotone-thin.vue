<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hk5y8xrjt"/><path class="ortw0s1jo"/><path class="z55i2tbmp"/><path class="rt75x1b6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:focus-session-duotone-thin" /></template>
<style>
.hk5y8xrjt {
  fill: currentColor;
  d: path("M5 14a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ortw0s1jo {
  d: path("M5 14a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.rt75x1b6c {
  d: path("M12 7V4");
}

.z55i2tbmp {
  d: path("m9 4 3 3 3 -3");
}

</style>
