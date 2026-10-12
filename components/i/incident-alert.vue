<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="gedkbpbls"/><path class="r8i1ocbvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:incident-alert" /></template>
<style>
.gedkbpbls {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.95 4.76l7.35 13.73q.95 1.76-1.05 1.76H4.75q-2 0-1.05-1.76l7.35-13.73q.95-1.76 1.9 0M12 9v5.5");
}

.r8i1ocbvm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
