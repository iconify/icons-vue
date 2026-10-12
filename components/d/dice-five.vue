<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="mv25dlxlh"/><path class="mindnib1o"/><path class="kqif8_bws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dice-five" /></template>
<style>
.kqif8_bws {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7.5h.01m2.29 5.9h.01m3.29 1.8h.01m-9.51-.95h.01m2.09 3.65h.01m-.01-4.86h.01M6 15.46h.01M6 10.6h.01");
}

.mindnib1o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7.8L12 12l7.25-4.2M12 12v8.4");
}

.mv25dlxlh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.3 3.75l5.19 3q1.3.75 1.3 2.25v6q0 1.5-1.3 2.25l-5.19 3q-1.3.75-2.6 0l-5.19-3q-1.3-.75-1.3-2.25V9q0-1.5 1.3-2.25l5.19-3q1.3-.75 2.6 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
