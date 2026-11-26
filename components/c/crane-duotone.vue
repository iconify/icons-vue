<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ihc_xk0rt"/><path class="dj-9w836s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:crane-duotone" /></template>
<style>
.dj-9w836s {
  d: path("M19 7L19 11M17 15L17 13C17 11.8954 17.8954 11 19 11C20.1046 11 21 11.8954 21 13L21 15");
}

.ihc_xk0rt {
  stroke-opacity: 0.4;
  d: path("M3 7L21 7M8 3L8 21M5 21L11 21M4 7L4 10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
