<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to0c2ub7t"><path class="edk05ab4u"/><path class="lgp-8qlsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-offset-left-two-tone" /></template>
<style>
.edk05ab4u {
  stroke-opacity: 0.4;
  d: path("M12 2L12 20M20 10L20 22");
}

.lgp-8qlsy {
  d: path("M4 2L4 8");
}

.to0c2ub7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
