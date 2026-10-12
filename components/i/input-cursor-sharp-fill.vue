<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wigmi2bok"/><path class="c0whh-vxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:input-cursor-sharp-fill" /></template>
<style>
.c0whh-vxy {
  fill: currentColor;
  d: path("M17.0074 17.3215L14.925 11.1884C14.8898 11.0849 14.8719 10.9763 14.8719 10.8669C14.8719 10.3146 15.3196 9.8669 15.8719 9.8669C15.9863 9.8669 16.0999 9.8865 16.2077 9.925L22.3358 12.1095C22.7341 12.2514 23 12.6286 23 13.0514C23 13.4347 22.7809 13.7843 22.4358 13.9514L20.1351 15.0656L18.8342 17.4751C18.6597 17.7984 18.3218 18 17.9543 18C17.5259 18 17.1451 17.7271 17.0074 17.3215Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wigmi2bok {
  d: path("M21 7L2 7L2 17L13 17M6 10L6 14");
}

</style>
