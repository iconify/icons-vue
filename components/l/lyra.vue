<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGXcFPJbep)" class="kqkuz82_g"/><path fill="url(#SVGZafFLr4k)" class="y5-ldqf1x"/><defs><linearGradient id="SVGXcFPJbep" x1="12" x2="12" y1="2.994" y2="21.001" gradientUnits="userSpaceOnUse"><stop class="vnu3zelit"/><stop offset="1" class="j4oi4gbng"/></linearGradient><linearGradient id="SVGZafFLr4k" x1="18.838" x2="5.267" y1="15.025" y2="19.988" gradientUnits="userSpaceOnUse"><stop class="hfshq8b9a"/><stop offset="1" class="lloww5bqb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lyra" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hfshq8b9a {
  stop-color: var(--svg-color--47d1c1, #47d1c1);
}

.j4oi4gbng {
  stop-color: var(--svg-color--37c4b1, #37c4b1);
}

.kqkuz82_g {
  d: path("m15.884 9.979l-3.134 3.145H4.812c-.574 0-.861-.658-.473-1.052l8.872-8.929a.495.495 0 0 1 .794.135l2.21 4.923a1.59 1.59 0 0 1-.33 1.778");
}

.lloww5bqb {
  stop-color: var(--svg-color--21bfa1, #21bfa1);
}

.vnu3zelit {
  stop-color: var(--svg-color--5adcd3, #5adcd3);
}

.y5-ldqf1x {
  d: path("M3 13.686c.18.242.827.563 1.947.563h12.321c.714 0 1.361.416 1.643 1.069l2.042 4.827a.62.62 0 0 1-.574.855H7.523a2.03 2.03 0 0 1-1.856-1.204z");
}

</style>
