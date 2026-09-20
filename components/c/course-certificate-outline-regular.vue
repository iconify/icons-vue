<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yxv11bcbk"/><path class="uxsptjbvt"/><path class="soorsrbax"/><path class="n8wwq96fg"/><path class="htfprqbon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:course-certificate-outline-regular" /></template>
<style>
.htfprqbon {
  d: path("M15 17v4l2 -2 2 2v-4");
}

.n8wwq96fg {
  d: path("M14 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.soorsrbax {
  d: path("M6 10h8");
}

.uxsptjbvt {
  d: path("M6 7h12");
}

.yxv11bcbk {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
