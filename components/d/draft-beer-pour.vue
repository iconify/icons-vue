<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="czfg-7bil"/><path class="lb7lqnp0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:draft-beer-pour" /></template>
<style>
.czfg-7bil {
  d: path("M4 3h7.5a2 2 0 0 1 2 2v3.75M8 9l1 12h9l1-12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lb7lqnp0y {
  d: path("M8.25 12q2.625-2.25 5.25 0t5.25 0");
}

</style>
