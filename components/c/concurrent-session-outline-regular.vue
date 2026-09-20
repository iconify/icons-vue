<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iymet_cml"/><path class="gwl0nvbom"/><path class="efcgw323v"/><path class="pbh8k3r0o"/><path class="jw1bp8juq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:concurrent-session-outline-regular" /></template>
<style>
.efcgw323v {
  d: path("M5 16a3 3 0 0 1 6 0");
}

.gwl0nvbom {
  d: path("M6 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.iymet_cml {
  d: path("M15.5 4H19a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V8l4 -4h3.5");
}

.jw1bp8juq {
  d: path("M13 16a3 3 0 0 1 6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pbh8k3r0o {
  d: path("M14 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
