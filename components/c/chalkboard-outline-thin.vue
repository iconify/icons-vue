<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gkj6vbuly"/><path class="ui32hib9b"/><path class="kwxihke4k"/><path class="wf6qyfbld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chalkboard-outline-thin" /></template>
<style>
.gkj6vbuly {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwxihke4k {
  d: path("M7 9h8");
}

.ui32hib9b {
  d: path("M5 20h14");
}

.wf6qyfbld {
  d: path("M7 13h5");
}

</style>
