<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s8sdj3bso"/><path class="hcmi4inus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-clock-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hcmi4inus {
  d: path("M16.5 10C19.5376 10 22 12.4624 22 15.5C22 18.5376 19.5376 21 16.5 21C13.4624 21 11 18.5376 11 15.5C11 12.4624 13.4624 10 16.5 10ZM16 13.1L16 16L18.9 16");
}

.s8sdj3bso {
  stroke-opacity: 0.4;
  d: path("M17.5015 6.5323L17.2136 6.0283C16.1803 4.2193 14.2325 3 12 3C8.6863 3 6 5.6863 6 9C3.7909 9 2 10.7909 2 13C2 15.2091 3.7909 17 6 17L8.1186 17");
}

</style>
