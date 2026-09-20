<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xgrfb-bqu"/><path class="nooweob_o"/><path class="gmrzwr9af"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:attribution-outline-regular" /></template>
<style>
.gmrzwr9af {
  d: path("M14 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nooweob_o {
  d: path("M3 10h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
