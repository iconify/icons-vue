<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qsmit-bka"/><path class="ly9_lzbqv"/><path clip-rule="evenodd" class="gcrij3bes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-dot-lock-sharp-duotone" /></template>
<style>
.gcrij3bes {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 12C14 13.1046 13.1046 14 12 14C10.8954 14 10 13.1046 10 12C10 10.8954 10.8954 10 12 10C13.1046 10 14 10.8954 14 12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ly9_lzbqv {
  d: path("M15 17L22 17L22 22L15 22ZM16.5 17L16.5 15C16.5 13.8954 17.3954 13 18.5 13C19.6046 13 20.5 13.8954 20.5 15L20.5 17");
}

.qsmit-bka {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 16L12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C17.2348 1 21.6155 4.6567 22.7273 9.555L20.775 10L15.4649 10C14.7732 8.8044 13.4805 8 12 8C9.7909 8 8 9.7909 8 12C8 14.2091 9.7909 16 12 16Z");
  stroke: none;
}

</style>
