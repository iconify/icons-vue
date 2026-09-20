<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b5bbp_b6e"/><path class="u2z_81bft"/><path class="xbibi3o1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:co-two-outline-regular" /></template>
<style>
.b5bbp_b6e {
  d: path("M5 18a4 4 0 0 1 2 -7 5 5 0 0 1 9 -1 4.5 4.5 0 0 1 3 8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u2z_81bft {
  d: path("M7.5 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.xbibi3o1e {
  d: path("M13 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
