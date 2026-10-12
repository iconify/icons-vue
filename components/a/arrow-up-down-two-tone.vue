<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vrem0jbde"/><path class="f-sv1wbyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-down-two-tone" /></template>
<style>
.f-sv1wbyp {
  d: path("M7 21L7 3M3 7L7 3L11 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vrem0jbde {
  stroke-opacity: 0.4;
  d: path("M17 3L17 21M21 17L17 21L13 17");
}

</style>
