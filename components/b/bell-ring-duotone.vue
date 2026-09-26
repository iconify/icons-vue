<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vuin9ubsk"/><path class="mmzbty-9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-ring-duotone" /></template>
<style>
.mmzbty-9y {
  d: path("M10.2679 20C10.6252 20.6188 11.2855 21 12 21C12.7145 21 13.3748 20.6188 13.7321 20M21 8C21 6.22 20.4722 4.48 19.4833 3M3 8C3 6.22 3.5278 4.48 4.5167 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vuin9ubsk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2C15.3137 2 18 4.68629 18 8C18 10.3517 18.4669 11.6977 18.8944 12.5528C19.1215 13.007 19.3311 13.3166 19.545 13.673C19.7216 13.9674 20 14.4387 20 15C20 16.1046 19.1046 17 18 17H6C4.8954 17 4 16.1046 4 15C4 14.4387 4.2784 13.9674 4.455 13.673C4.6689 13.3166 4.8785 13.007 5.1056 12.5528C5.5331 11.6977 6 10.3517 6 8C6 4.68629 8.68629 2 12 2Z");
  stroke: none;
}

</style>
