<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="fb1y2ebow"/><path class="ki85wji_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ev-charger-fill" /></template>
<style>
.fb1y2ebow {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 23L2 23C1.4477 23 1 22.5523 1 22L1 5C1 2.7908 2.7908 1 5 1L11 1C13.2092 1 15 2.7908 15 5L15 21L22 21C22.5523 21 23 21.4477 23 22C23 22.5523 22.5523 23 22 23L14 23ZM9.8 8.6C9.9298 8.4269 10 8.2164 10 8C10 7.4477 9.5523 7 9 7C8.6852 7 8.3889 7.1482 8.2 7.4L5.2 11.4C5.0702 11.5731 5 11.7836 5 12C5 12.5523 5.4477 13 6 13L8 13L6.2 15.4C6.0702 15.5731 6 15.7836 6 16C6 16.5523 6.4477 17 7 17C7.3148 17 7.6111 16.8518 7.8 16.6L10.8 12.6C10.9298 12.4269 11 12.2164 11 12C11 11.4477 10.5523 11 10 11L8 11L9.8 8.6ZM18 5L22 5C22.5523 5 23 5.4477 23 6L23 8.5C23 9.8807 21.8807 11 20.5 11L19.5 11C18.1193 11 17 9.8807 17 8.5L17 6C17 5.4477 17.4477 5 18 5Z");
  stroke: none;
}

.ki85wji_q {
  d: path("M14 17L18 17C19.1046 17 20 16.1046 20 15L20 10M22 6L22 4M18 6L18 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
