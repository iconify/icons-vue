<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oyzylue_v"/><path clip-rule="evenodd" class="bkv811o2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:before-and-after-duotone" /></template>
<style>
.bkv811o2j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 4L19 4C21.2092 4 23 5.7908 23 8L23 16C23 18.2092 21.2092 20 19 20L13 20L13 22.0001C13 22.5524 12.5523 23.0001 12 23.0001C11.4477 23.0001 11 22.5524 11 22.0001L11 19L11 12L11 4.9922L11 2.0001C11 1.4478 11.4477 1.0001 12 1.0001C12.5523 1.0001 13 1.4478 13 2.0001Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oyzylue_v {
  stroke-opacity: 0.4;
  d: path("M8 19H5C3.3431 19 2 17.6569 2 16V8C2 6.3431 3.3431 5 5 5H8");
}

</style>
