<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="l-m5kqb5w"/><path class="cab6d98hu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:body-fat" /></template>
<style>
.cab6d98hu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 12.5h.01m4.49 4.5h.01");
}

.l-m5kqb5w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c3.5 4 6.75 7.75 6.75 11.5a6.75 6.75 0 0 1-13.5 0c0-3.75 3.25-7.5 6.75-11.5M9.75 17l4.5-4.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
