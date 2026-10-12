<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="wjflj_qvk"/><path class="kg648e1tc"/><path class="klgrndbjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bison" /></template>
<style>
.kg648e1tc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 7.25C4.75 6.5 4.5 5.25 5 4");
}

.klgrndbjw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 10.25h.01");
}

.wjflj_qvk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6.5C11 4.25 13 3.25 15 3.25c2.5 0 4 1.5 4.5 3.5l.75 3c.3 1.25.5 2.5.5 3.75v6.75H18.5v-3.5h-5.75v3.5H10V16.5H9l-1.75 2l-1.75-1.75c-1.5-.5-2.25-1.5-2.25-2.75l.25-3.5C3.75 8.5 5 7.25 6.75 7Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
