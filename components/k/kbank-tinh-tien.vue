<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="oj1l9-0dp"/><path class="yt737bbcz"/><path class="pqcw8wbra"/><path class="wic0ftbxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kbank-tinh-tien" /></template>
<style>
.oj1l9-0dp {
  d: path("M14.026 16.433a10.117 10.117 0 0 1 19.948-.002");
}

.pqcw8wbra {
  d: path("M9.395 5.5h29.21A3.886 3.886 0 0 1 42.5 9.395v29.21a3.886 3.886 0 0 1-3.895 3.895H9.395A3.886 3.886 0 0 1 5.5 38.605V9.395A3.886 3.886 0 0 1 9.395 5.5");
}

.wic0ftbxl {
  d: path("m42.258 13.166l-12.93 5.281c-3.289 1.343-7.367 1.343-10.655 0l-12.93-5.281");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yt737bbcz {
  d: path("m20.087 15.045l1.998 2.386l5.71-6.408");
}

</style>
