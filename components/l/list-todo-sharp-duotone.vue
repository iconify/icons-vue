<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="f8tucz9uh"/><path class="df7stpbos"/><path class="vjufq2vmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-todo-sharp-duotone" /></template>
<style>
.df7stpbos {
  stroke-opacity: 0.4;
  d: path("M11 7L23 7M11 18L23 18");
}

.f8tucz9uh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3L8 3C8.5523 3 9 3.4477 9 4L9 10C9 10.5523 8.5523 11 8 11L2 11C1.4477 11 1 10.5523 1 10L1 4C1 3.4477 1.4477 3 2 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vjufq2vmo {
  d: path("M1.7071 17.7071L4 20L8.2929 15.7071");
}

</style>
