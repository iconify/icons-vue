<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s5z_cliac"/><path class="kc_u2cbhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-pick-screen" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kc_u2cbhl {
  d: path("m18.987 16.159l.354.354a2 2 0 0 1 0 2.828a2 2 0 0 1-2.828 0l-.354-.354a2 2 0 0 1 0-2.828a2 2 0 0 1 2.828 0");
}

.s5z_cliac {
  d: path("M3.25 7.75v-2.5a2 2 0 0 1 2-2h2.5m6 0h2.5a2 2 0 0 1 2 2v2.5m-15 6v2.5a2 2 0 0 0 2 2h2.5m.5-10l2 2m2.116-.005l3.889 3.889a1.5 1.5 0 0 1 0 2.121a1.5 1.5 0 0 1-2.121 0l-3.889-3.889a1.5 1.5 0 0 1 0-2.121a1.5 1.5 0 0 1 2.121 0");
}

</style>
