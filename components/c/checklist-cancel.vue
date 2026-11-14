<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pfcz1uubt"/><path class="vfj4pnbqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checklist-cancel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfcz1uubt {
  d: path("M4.5 2.75h.75A1.75 1.75 0 0 1 7 4.5v.75A1.75 1.75 0 0 1 5.25 7H4.5a1.75 1.75 0 0 1-1.75-1.75V4.5A1.75 1.75 0 0 1 4.5 2.75m0 7h.75A1.75 1.75 0 0 1 7 11.5v.75A1.75 1.75 0 0 1 5.25 14H4.5a1.75 1.75 0 0 1-1.75-1.75v-.75A1.75 1.75 0 0 1 4.5 9.75m0 7h.75A1.75 1.75 0 0 1 7 18.5v.75A1.75 1.75 0 0 1 5.25 21H4.5a1.75 1.75 0 0 1-1.75-1.75v-.75a1.75 1.75 0 0 1 1.75-1.75");
}

.vfj4pnbqz {
  d: path("M3.75 4.5L5.25 6L8.5 2.5m2 2.25H21m-10.5 7H21m-5.5 3.75l5 5m0-5l-5 5");
}

</style>
