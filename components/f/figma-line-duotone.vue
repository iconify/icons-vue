<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mw9a2m02n"/><path class="a7_qblosi"/><path class="vgpahk0tv"/><path class="v2kjfgb-s"/><path class="jehd3zbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:figma-line-duotone" /></template>
<style>
.a7_qblosi {
  d: path("M8.66683 8.66675H12.0002V15.3334H8.66683C6.82588 15.3334 5.3335 13.841 5.3335 12.0001C5.3335 10.1591 6.82588 8.66675 8.66683 8.66675Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jehd3zbqn {
  d: path("M15.3333 2H12V8.66667H15.3333C17.1743 8.66667 18.6667 7.17428 18.6667 5.33333C18.6667 3.49238 17.1743 2 15.3333 2Z");
}

.mw9a2m02n {
  d: path("M8.66683 2H12.0002V8.66667H8.66683C6.82588 8.66667 5.3335 7.17428 5.3335 5.33333C5.3335 3.49238 6.82588 2 8.66683 2Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.v2kjfgb-s {
  d: path("M12.0002 15.3333H8.66683C6.82588 15.3333 5.3335 16.8256 5.3335 18.6666C5.3335 20.5075 6.82588 21.9999 8.66683 21.9999C10.5078 21.9999 12.0002 20.5075 12.0002 18.6666V15.3333Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vgpahk0tv {
  d: path("M15.3333 15.3334C17.1743 15.3334 18.6667 13.841 18.6667 12.0001C18.6667 10.1591 17.1743 8.66675 15.3333 8.66675C13.4924 8.66675 12 10.1591 12 12.0001C12 13.841 13.4924 15.3334 15.3333 15.3334Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
