<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e2hxaobyi"/><path class="c5yb8bdcb"/><path class="pcr6xabis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-alert" /></template>
<style>
.c5yb8bdcb {
  d: path("M12 7V13");
}

.e2hxaobyi {
  d: path("M22 12C22 17.52285 17.52285 22 12 22C6.47715 22 2 17.52285 2 12C2 6.47715 6.47715 2 12 2C17.52285 2 22 6.47715 22 12Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pcr6xabis {
  fill: currentColor;
  d: path("M13 17C13 17.55228 12.55228 18 12 18C11.44772 18 11 17.55228 11 17C11 16.44772 11.44772 16 12 16C12.55228 16 13 16.44772 13 17Z");
  stroke: none;
}

</style>
