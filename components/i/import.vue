<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mw0u8cbll"/><path class="g0o42lu3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:import" /></template>
<style>
.g0o42lu3z {
  d: path("m9 11.5l3 3l3-3");
}

.mw0u8cbll {
  d: path("M7.5 8.5h-1A2.5 2.5 0 0 0 4 11v6.5A2.5 2.5 0 0 0 6.5 20h11a2.5 2.5 0 0 0 2.5-2.5V11a2.5 2.5 0 0 0-2.5-2.5h-1M12 3v11.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
