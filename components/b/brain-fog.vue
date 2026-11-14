<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqa1j3b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brain-fog" /></template>
<style>
.hqa1j3b_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.5C10.75 3 7.5 3 6.75 5.5c-2.5.25-4 3.25-2.5 5.5c-1.5 2.25-.5 5.75 2.5 6c.581 1.937 2.813 2.673 4.254 1.977M12 4.5c1.25-1.5 4.5-1.5 5.25 1c2.5.25 4 3.25 2.5 5.5c.551.827.765 1.822.666 2.763M12 4.5v11.7m4 5.3a2.25 2.25 0 0 1 0-4.5a2.5 2.5 0 0 1 4.5 1.5a1.5 1.5 0 0 1 0 3Z");
}

</style>
