<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x2vm1eh6r"/><path class="va9i39bae"/><path class="j4a3yvbid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:blood-test-outline-regular" /></template>
<style>
.j4a3yvbid {
  d: path("m12 9 3 3a4 4 0 0 1 -6 0Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.va9i39bae {
  d: path("M7 3h10");
}

.x2vm1eh6r {
  d: path("M9 3v15h6V3");
}

</style>
