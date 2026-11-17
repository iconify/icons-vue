<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e1otdgb2g"/><path class="ngysh-w9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:audio-lines-low-two-tone" /></template>
<style>
.e1otdgb2g {
  stroke-opacity: 0.4;
  d: path("M8 10V14M16 11V13");
}

.ngysh-w9y {
  d: path("M4 11V13M12 8V16M20 10V14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
