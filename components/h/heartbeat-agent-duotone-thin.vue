<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ft030md1w"/><path class="yi9whke5t"/><path class="skbifdbcx"/><path class="a-m7xvbdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:heartbeat-agent-duotone-thin" /></template>
<style>
.a-m7xvbdg {
  d: path("M10 18h3l2.5 -2.5L18 18h3");
}

.ft030md1w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.yi9whke5t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 18h3l2.5 -2.5L18 18h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
