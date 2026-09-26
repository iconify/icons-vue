<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uvuo-obhr"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:droplet-off-sharp-fill" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uvuo-obhr {
  fill: currentColor;
  d: path("M9.2817 5.0391L12.0001 2L17.9629 8.6666C19.6179 10.5172 20.3497 13.0678 19.8403 15.5977L9.2817 5.0391ZM18.5678 18.5678C17.0723 20.718 14.6191 22 12 22C7.5817 22 4 18.4183 4 14C4 12.0322 4.7253 10.1334 6.0371 8.6666L7.2786 7.2786Z");
  stroke: none;
}

</style>
