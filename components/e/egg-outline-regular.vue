<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q-5l-qhcw"/><path class="v29fxrpgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:egg-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q-5l-qhcw {
  d: path("M12 21c-4 0 -6 -3 -6 -7C6 9 9 4 12 4s6 5 6 10c0 4 -2 7 -6 7");
}

.v29fxrpgx {
  d: path("m8 13 2 2 2 -2 2 2 2 -2");
}

</style>
