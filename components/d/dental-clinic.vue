<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ng896ibfx"/><path class="uncg9e5gx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-clinic" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ng896ibfx {
  d: path("M6.625 11h10.75A2.625 2.625 0 0 1 20 13.625v4.75A2.625 2.625 0 0 1 17.375 21H6.625A2.625 2.625 0 0 1 4 18.375v-4.75A2.625 2.625 0 0 1 6.625 11M12 3.5c-1-1-3.5-1.25-3.5 1.5c0 1.75.75 2.5 1 3.75l.75 2.25H11l1-2.5l1 2.5h.75l.75-2.25c.25-1.25 1-2 1-3.75c0-2.75-2.5-2.5-3.5-1.5");
}

.uncg9e5gx {
  d: path("M9.75 21v-4.5a2.25 2.25 0 0 1 4.5 0V21");
}

</style>
