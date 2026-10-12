<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="etp_2wjkz"/><circle class="aqhok2bbj"/><path class="o9vxhccxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hair-tie-sharp" /></template>
<style>
.aqhok2bbj {
  cx: 12px;
  cy: 12px;
  r: 4px;
}

.etp_2wjkz {
  d: path("M12 3.6a1.85 1.85 0 0 1 3.21.64a1.85 1.85 0 0 1 2.73 1.82a1.85 1.85 0 0 1 1.82 2.73A1.85 1.85 0 0 1 20.4 12a1.85 1.85 0 0 1-.64 3.21a1.85 1.85 0 0 1-1.82 2.73a1.85 1.85 0 0 1-2.73 1.82a1.85 1.85 0 0 1-3.21.64a1.85 1.85 0 0 1-3.21-.64a1.85 1.85 0 0 1-2.73-1.82a1.85 1.85 0 0 1-1.82-2.73A1.85 1.85 0 0 1 3.6 12a1.85 1.85 0 0 1 .64-3.21a1.85 1.85 0 0 1 1.82-2.73a1.85 1.85 0 0 1 2.73-1.82A1.85 1.85 0 0 1 12 3.6Z");
}

.o9vxhccxn {
  d: path("M15.2 6.46a6.4 6.4 0 0 1 2.81 3.35m-.47 5.39a6.4 6.4 0 0 1-3.35 2.81m-5.39-.47a6.4 6.4 0 0 1-2.81-3.35m.47-5.39a6.4 6.4 0 0 1 3.35-2.81");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
