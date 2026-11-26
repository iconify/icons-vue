<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s6hrhreql"/><path class="nnndz3ufg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-signal-duotone" /></template>
<style>
.nnndz3ufg {
  d: path("M14 21V18M18 21V14M22 21V10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s6hrhreql {
  stroke-opacity: 0.4;
  d: path("M18.1265 9.002C18.0845 9.0007 18.0423 9 18 9C18 5.6863 15.3137 3 12 3C8.6863 3 6 5.6863 6 9C3.7909 9 2 10.7909 2 13C2 15.2091 3.7909 17 6 17H10.127");
}

</style>
