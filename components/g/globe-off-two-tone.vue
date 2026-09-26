<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dzzajs9ee"/><path class="tv3dr9bzz"/><path class="ndrwukb5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-off-two-tone" /></template>
<style>
.dzzajs9ee {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.7782 19.7782C17.7876 21.7688 15.0376 23 12 23C5.9249 23 1 18.0751 1 12C1 8.9624 2.2312 6.2124 4.2218 4.2218L19.7782 19.7782Z");
  stroke: none;
}

.ndrwukb5e {
  stroke-opacity: 0.4;
  d: path("M8.3456 2.6888C9.4776 2.2442 10.7103 2 12 2C17.5228 2 22 6.4772 22 12C22 13.2897 21.7558 14.5224 21.3112 15.6544M17.6569 12L22 12M10.1522 4.4954C10.6735 3.6344 11.2894 2.7994 12 2C14.2163 4.4933 15.5116 7.332 15.8859 10.2291");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tv3dr9bzz {
  d: path("M19.0711 19.0711C17.2614 20.8807 14.7614 22 12 22M12 22C6.4772 22 2 17.5228 2 12M12 22C13.7626 20.0171 14.9427 17.8157 15.5403 15.5403M12 22C9.3333 19 8 15.5 8 12C8 10.8134 8.1532 9.6268 8.4597 8.4597M2 12C2 9.2386 3.1193 6.7386 4.9289 4.9289M2 12H12M2 2L22 22");
}

</style>
