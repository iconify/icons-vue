<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ay0o1u2ti"/><path class="ko0wz_brv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-keyhole-duocolor-round" /></template>
<style>
.ay0o1u2ti {
  stroke-opacity: 0.4;
  d: path("M9 10V6a3 3 0 0 1 6 0v4");
}

.ko0wz_brv {
  d: path("M4 14a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v3a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm7 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 1v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
