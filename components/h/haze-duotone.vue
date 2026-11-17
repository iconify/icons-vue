<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yd2_60b6u"/><path class="zts0mdbub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:haze-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yd2_60b6u {
  stroke-opacity: 0.4;
  d: path("M7.5 12C7.5 9.515 9.515 7.5 12 7.5C14.485 7.5 16.5 9.515 16.5 12M2 12H3.5M20.5 12H22M4.929 4.929L5.99 5.99M19.071 4.929L18.01 5.99M12 3.5V2");
}

.zts0mdbub {
  d: path("M4 17H20M5 22H10M14 22H19");
}

</style>
