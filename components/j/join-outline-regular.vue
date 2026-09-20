<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x5-v1c34k"/><path class="r1giuh9in"/><path class="l517yxbln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:join-outline-regular" /></template>
<style>
.l517yxbln {
  d: path("M12 9v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r1giuh9in {
  d: path("M10 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.x5-v1c34k {
  d: path("M2 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

</style>
