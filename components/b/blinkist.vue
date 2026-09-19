<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="cimmok02t"/><path class="bukvn6bwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blinkist" /></template>
<style>
.bukvn6bwo {
  d: path("M45.5 23.784c-.003 11.874-9.631 21.497-21.506 21.494S2.497 35.647 2.5 23.773a21.5 21.5 0 0 1 10.587-18.52a2.33 2.33 0 0 1 2.83.362l8.036 8.071l8.153-8.071a2.33 2.33 0 0 1 2.83-.361A21.51 21.51 0 0 1 45.5 23.784");
}

.cimmok02t {
  d: path("M31.442 23.784a7.442 7.442 0 0 1-14.873 0C16.57 19.673 24 13.698 24 13.698s7.442 5.975 7.442 10.086");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
