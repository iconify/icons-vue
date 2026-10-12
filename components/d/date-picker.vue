<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="khounccao"/><path class="h6wfn2b6s"/><path class="rtym4acgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:date-picker" /></template>
<style>
.h6wfn2b6s {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 14h.01M11 14h.01m-3.26 3.25h.01");
}

.khounccao {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 20.25h-5.5a2.5 2.5 0 0 1-2.5-2.5v-10a2.5 2.5 0 0 1 2.5-2.5h11.5a2.5 2.5 0 0 1 2.5 2.5v4M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

.rtym4acgl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.95 14.51l5.35 1.98q.7.26-.02.48l-1.81.56q-.72.22-.94.94l-.56 1.81q-.22.72-.48.02l-1.98-5.35q-.26-.7.44-.44");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
