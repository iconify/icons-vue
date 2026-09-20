<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zcnxk5bij"/><path class="mycgd0b6x"/><path class="vdktr42cl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:eyedropper-outline-regular" /></template>
<style>
.mycgd0b6x {
  d: path("m14 9 -7 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vdktr42cl {
  d: path("M3.5 18.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zcnxk5bij {
  d: path("M13 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
