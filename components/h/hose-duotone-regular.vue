<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kclcpsdct"/><path class="s3aj37b5a"/><path class="rgnpgnbjr"/><path class="nvz2drb7k"/><path class="lbejogjbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hose-duotone-regular" /></template>
<style>
.kclcpsdct {
  fill: currentColor;
  d: path("M8 8h8v4H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lbejogjbx {
  d: path("M8 10c-3 0 -4 3 -4 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nvz2drb7k {
  d: path("M10 12v5h3");
}

.rgnpgnbjr {
  d: path("M16 10h5");
}

.s3aj37b5a {
  d: path("M8 8h8v4H8Z");
}

</style>
