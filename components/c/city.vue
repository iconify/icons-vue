<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvmya5bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:city" /></template>
<style>
.cvmya5bja {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M9 21V5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v16M12 7h.01M12 11h.01M12 15h.01M6 13h.01M6 17h.01M18 17h.01M9 9H5a2 2 0 0 0-2 2v10m12-8h4a2 2 0 0 1 2 2v6");
}

</style>
