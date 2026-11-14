<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iqp6c-z_r"/><path class="sez-idbmd"/><path class="z4gnbmbjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-check-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iqp6c-z_r {
  d: path("M2.03516 8.75H21.965M7 3.785V2.25M17 3.785V2.25");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.sez-idbmd {
  d: path("M10 21.75H14C17.7712 21.75 19.6569 21.75 20.8284 20.5784C22 19.4069 22 17.5212 22 13.75V11.75C22 7.9788 22 6.0931 20.8284 4.9216C19.6569 3.75 17.7712 3.75 14 3.75H10C6.2288 3.75 4.3431 3.75 3.1716 4.9216C2 6.0931 2 7.9788 2 11.75V13.75C2 17.5212 2 19.4069 3.1716 20.5784C4.3431 21.75 6.2288 21.75 10 21.75Z");
}

.z4gnbmbjf {
  d: path("M9.5 15.4L11.1667 17.25L14.5 13.25");
}

</style>
