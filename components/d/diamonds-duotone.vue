<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tqmpdsb2r"/><path clip-rule="evenodd" class="piyz5dbhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diamonds-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.piyz5dbhq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.6213 16.6213L17.1213 19.1213C15.9498 20.2929 14.0502 20.2929 12.8786 19.1213L7.8787 14.1213C6.7071 12.9498 6.7071 11.0502 7.8787 9.8786L12.8787 4.8787C14.0502 3.7071 15.9498 3.7071 17.1214 4.8787L22.1213 9.8787C23.2929 11.0502 23.2929 12.9498 22.1213 14.1214Z");
  stroke: none;
}

.tqmpdsb2r {
  stroke-opacity: 0.4;
  d: path("M8.4153 18.9126C8.1021 18.8169 7.8173 18.6457 7.5858 18.4142L2.5858 13.4142C1.8047 12.6332 1.8047 11.3668 2.5858 10.5858L7.5858 5.5858C7.8173 5.3543 8.1021 5.1831 8.4153 5.0874");
}

</style>
