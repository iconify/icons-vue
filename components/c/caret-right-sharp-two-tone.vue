<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lrsmktbfe"/><path class="rsy5g76ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-right-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lrsmktbfe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.5039 12.8638L6.5039 19.8638C5.8372 20.2527 5 19.7718 5 19L5 5C5 4.2282 5.8372 3.7473 6.5039 4.1362L18.5039 11.1362C19.1654 11.5221 19.1654 12.4779 18.5039 12.8638Z");
  stroke: none;
}

.rsy5g76ue {
  d: path("M18 12L6 19L6 5L18 12Z");
}

</style>
