<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s84krac4d"/><circle class="f1zl3cc-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:anemometer" /></template>
<style>
.f1zl3cc-e {
  cx: 12px;
  cy: 8px;
  r: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s84krac4d {
  d: path("M6.25 8h4m3.5 0h3.75M12 9.75v11.5m-3 0h6M6.25 4.75v6.5a3.25 3.25 0 0 1 0-6.5m14.5 0v6.5a3.25 3.25 0 0 1 0-6.5");
}

</style>
