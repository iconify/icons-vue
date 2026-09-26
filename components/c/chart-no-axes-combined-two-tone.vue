<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b24wgm90r"/><path class="fm703rmtm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-no-axes-combined-two-tone" /></template>
<style>
.b24wgm90r {
  stroke-opacity: 0.4;
  d: path("M22 3L13.5984 10.0013C13.2465 10.2945 12.7405 10.3112 12.37 10.0418L8.1911 7.0026C7.7931 6.7132 7.2437 6.7563 6.8958 7.1042L2 12");
}

.fm703rmtm {
  d: path("M4 21L4 17M8 21L8 12M12 21L12 15M16 21L16 13.5M20 21L20 10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
