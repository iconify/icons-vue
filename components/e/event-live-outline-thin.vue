<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="enrpg0aoq"/><path class="oxemtublz"/><path class="j9_-r5bkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-live-outline-thin" /></template>
<style>
.enrpg0aoq {
  d: path("M9 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j9_-r5bkt {
  d: path("M17 7c3 3 3 7 0 10");
}

.oxemtublz {
  d: path("M7 7c-3 3 -3 7 0 10");
}

</style>
