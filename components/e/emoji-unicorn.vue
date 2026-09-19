<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="tp1ruqtpy"/><path class="zj3t3loje"/><path class="zdp1w9bvk"/><path class="hq-p6mt7n"/><circle class="srgrs_9mo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-unicorn" /></template>
<style>
.hq-p6mt7n {
  d: path("M32.537 15.109s10.064 4.49 3.719 15.144c0 0-3.664 4.473.426 9.273");
}

.srgrs_9mo {
  cx: 15.156px;
  cy: 19.045px;
  r: 1.363px;
}

.tp1ruqtpy {
  d: path("M38.355 25.079c1.205 1.61 4.46 4.554 4.12 11.067m-23.889-9.963s9.021 5.536 2.079 14.481m-5.242-28.296L5.5 7.336l7.446 8.345");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zdp1w9bvk {
  d: path("M19.586 8.883s15.16-2.74 13.603 13.603");
}

.zj3t3loje {
  d: path("M22.503 20.367c.374 5.695-6.354 6.613-8.148 7.044c-.227.054-.43.17-.595.335l-1.515 1.515a1.27 1.27 0 0 1-.898.372H8.953c-.82 0-1.548-.525-1.807-1.303l-.362-1.085a1.9 1.9 0 0 1 .174-1.583l5.988-9.98l3.22-3.22l-1.442-4.707s5.318-.476 5.735 3.634c0 0 11.537 1.664 7.192 13.21c0 0-1.107 4.055 1.619 7.624");
}

</style>
