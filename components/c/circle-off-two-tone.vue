<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mdxxtccik"/><path class="pz0ayg2al"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-off-two-tone" /></template>
<style>
.mdxxtccik {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.7782 19.7782C17.7876 21.7688 15.0376 23 12 23C5.9249 23 1 18.0751 1 12C1 8.9624 2.2312 6.2124 4.2218 4.2218L19.7782 19.7782ZM7.6385 3.3959C7.4 3.1574 7.2978 2.8148 7.3667 2.4847C7.4355 2.1546 7.6661 1.8813 7.98 1.758C9.2251 1.2686 10.5812 1 12 1C18.0751 1 23 5.9249 23 12C23 13.4188 22.7314 14.7749 22.2422 16.0201C22.1189 16.3341 21.8456 16.5648 21.5154 16.6336C21.1851 16.7025 20.8424 16.6002 20.6039 16.3617L7.6385 3.3959Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pz0ayg2al {
  d: path("M19.0711 19.0711C17.2614 20.8807 14.7614 22 12 22C6.4772 22 2 17.5228 2 12C2 9.2386 3.1193 6.7386 4.9289 4.9289M2 2L22 22");
}

</style>
