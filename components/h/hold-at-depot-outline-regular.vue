<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e77gki8ci"/><path class="n92b0ebji"/><path class="m7aa3ibix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hold-at-depot-outline-regular" /></template>
<style>
.e77gki8ci {
  d: path("M2 20V10l3 -3h14l3 3v10");
}

.m7aa3ibix {
  d: path("M14.5 11v6");
}

.n92b0ebji {
  d: path("M9.5 11v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
