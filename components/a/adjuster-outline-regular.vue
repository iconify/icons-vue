<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pemn838wn"/><path class="ia4sldbfw"/><path class="vleiqby2b"/><path class="ljhme5bvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:adjuster-outline-regular" /></template>
<style>
.ia4sldbfw {
  d: path("M3 21a9 9 0 0 1 18 0");
}

.ljhme5bvp {
  d: path("M11.5 16.5 15 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pemn838wn {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.vleiqby2b {
  d: path("M9 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
