<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u8h66mbjf"/><path class="rno54ybbk"/><path class="eu9kkgbdm"/><path class="m27ljac1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:laser-duotone-regular" /></template>
<style>
.eu9kkgbdm {
  d: path("M9 12h12");
}

.m27ljac1c {
  d: path("m18 9 3 3 -3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rno54ybbk {
  d: path("M3 7h6v10H3Z");
}

.u8h66mbjf {
  fill: currentColor;
  d: path("M3 7h6v10H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
