<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="rjc1od8nf"/><path class="uastzoo4t"/><path class="kue4qbc3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clock-alert" /></template>
<style>
.kue4qbc3w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 20.75h.01");
}

.rjc1od8nf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.25A9.25 9.25 0 1 1 21.25 12");
}

.uastzoo4t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.25V12l-3 2m9.5.5v3.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
