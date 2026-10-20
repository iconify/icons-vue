<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oe-hqkn-s"/><path class="yyl3jgbsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gripper-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oe-hqkn-s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 10C16 12.2091 14.2091 14 12 14C9.7909 14 8 12.2091 8 10C8 7.7909 9.7909 6 12 6C14.2091 6 16 7.7909 16 10Z");
  stroke: none;
}

.yyl3jgbsr {
  d: path("M12 2L12 7M14.4575 11.7207L19.5841 15.4104C20.0353 15.7351 20.1351 16.3655 19.8061 16.8137L16 22M9.5425 11.7207L4.4159 15.4104C3.9647 15.7351 3.8649 16.3655 4.1939 16.8137L8 22M15 10C15 11.6569 13.6569 13 12 13C10.3431 13 9 11.6569 9 10C9 8.3431 10.3431 7 12 7C13.6569 7 15 8.3431 15 10Z");
}

</style>
