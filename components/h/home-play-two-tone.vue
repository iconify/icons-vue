<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l3w48acwr"/><path class="n85n2ab8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-play-two-tone" /></template>
<style>
.l3w48acwr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.0605 2.71C11.1795 1.76 12.8205 1.76 13.9395 2.71L21.0005 8.69C21.5976 9.26 22 10.1 22 10.93V19C21.9999 20.66 20.6568 22 19 22H5C3.3432 22 2.0001 20.66 2 19V10.93C2 10.05 2.3877 9.21 3.0605 8.64L10.0605 2.71Z");
  stroke: none;
}

.n85n2ab8i {
  d: path("M13.2928 3.47L20.2928 9.4C20.7414 9.78 21 10.34 21 10.93V19C21 20.1 20.1046 21 19 21H5C3.8954 21 3 20.1 3 19V10.93C3 10.34 3.2586 9.78 3.7072 9.4L10.7072 3.47C11.4532 2.84 12.5468 2.84 13.2928 3.47Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
