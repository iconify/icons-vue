<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nukscg80z"/><path class="u0-7g4ztn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heated-shelter" /></template>
<style>
.nukscg80z {
  d: path("m3 13.25l9-6.5l9 6.5");
}

.u0-7g4ztn {
  d: path("M5.5 11.5V21h13v-9.5m-11-4.25q-1-1.25 0-2.5t0-2.25m9 4.75q-1-1.25 0-2.5t0-2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
