<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="xbl8g-bhr"/><path class="z9m_ypwjr"/><path class="ofgvd-7kh"/><path class="nprl3gbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lisp" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nprl3gbjq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.132 4.949c13.03.967 17.296 10.335 9.357 20.279m.001 0c-7.76 11.922 3.001 18.206 13.404 15.976");
}

.ofgvd-7kh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.82 36.953c-5.992-6.424-1.722-14.292 2.416-22.29M9.912 14.55c1.461 6.8 3.026 8.777 3.9 10.785m.01.004c1.425-4.116 3.373-7.654 5.726-10.744l2.688.068");
}

.xbl8g-bhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.818 33.4l2.987.008c-2.115-8.121-5.81-15.406-9.992-22.432l-2.904.02");
}

.z9m_ypwjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.91 10.996c5.991 6.423 1.722 14.292-2.416 22.289m12.324.115c-1.461-6.802-3.026-8.778-3.9-10.787m-.01-.003c-1.425 4.116-3.373 7.654-5.726 10.743l-2.688-.068M9.912 14.55l-2.988-.01c2.116 8.122 5.81 15.406 9.993 22.432l2.904-.019");
}

</style>
