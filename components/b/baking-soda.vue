<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t_nitgakt"/><path class="rgtjrzndh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baking-soda" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rgtjrzndh {
  d: path("M9 14a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.t_nitgakt {
  d: path("M7.625 6.5h8.75A2.625 2.625 0 0 1 19 9.125v9.75a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 18.875v-9.75A2.625 2.625 0 0 1 7.625 6.5M6 4.625l.576-1.081A1.5 1.5 0 0 1 7.9 2.75h8.2a1.5 1.5 0 0 1 1.324.794L18 4.625A1.275 1.275 0 0 1 16.875 6.5h-9.75A1.275 1.275 0 0 1 6 4.625");
}

</style>
