<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pmkf16brp"/><circle class="malaqrb-i"/><path class="ybhviczra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:insurance-claim-sharp" /></template>
<style>
.malaqrb-i {
  cx: 12px;
  cy: 17.25px;
  r: 4px;
}

.pmkf16brp {
  d: path("M3.25 11.75a8.75 8.75 0 0 1 17.5 0a3.75 3.75 0 0 0-5.83 0a3.75 3.75 0 0 0-5.84 0a3.75 3.75 0 0 0-5.83 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ybhviczra {
  d: path("m13.13 16.27l-.35-.75h-1.94v.86c0 1.22 2.34.61 2.34 1.78v.83h-2.018l-.292-.73");
}

</style>
