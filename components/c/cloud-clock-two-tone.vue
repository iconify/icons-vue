<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g5xzfsvck"/><path class="m8-elsgfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-clock-two-tone" /></template>
<style>
.g5xzfsvck {
  stroke-opacity: 0.4;
  d: path("M17.2136 6.0283C16.1803 4.2193 14.2325 3 12 3C8.6863 3 6 5.6863 6 9C3.7909 9 2 10.7909 2 13C2 15.2091 3.7909 17 6 17H7.1186");
}

.m8-elsgfk {
  d: path("M16.5 10C19.5376 10 22 12.4624 22 15.5C22 18.5376 19.5376 21 16.5 21C13.4624 21 11 18.5376 11 15.5C11 12.4624 13.4624 10 16.5 10ZM16 14.1V16H17.9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
