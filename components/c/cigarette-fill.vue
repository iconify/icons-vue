<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dngycccmg"/><path class="ohoihvb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cigarette-fill" /></template>
<style>
.dngycccmg {
  fill: currentColor;
  d: path("M3.5 15L17.5 15C18.3284 15 19 15.6716 19 16.5L19 20.5C19 21.3284 18.3284 22 17.5 22L3.5 22C2.1193 22 1 20.8807 1 19.5L1 17.5C1 16.1193 2.1193 15 3.5 15Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ohoihvb9x {
  d: path("M22 16L22 21M18 12L13.5 12C11.0147 12 9 9.9853 9 7.5C9 5.6082 10.1832 3.9184 11.9609 3.2714M16 3C17.6569 3 19 4.3431 19 6L19 7.5C20.6569 7.5 22 8.8431 22 10.5L22 12M19 7.5L17.5 7.5");
}

</style>
