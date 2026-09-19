<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="a637lrqol"/><path class="adom_wh5o"/><path class="we8gaou1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:clanguage" /></template>
<style>
.a637lrqol {
  d: path("M29.388 27.264a6.406 6.406 0 1 1 .116-6.745");
}

.adom_wh5o {
  d: path("M33.728 30.388a11.896 11.896 0 1 1 .216-12.524m-4.44 2.656l4.44-2.656m-.216 12.524l-4.34-3.124");
}

.we8gaou1s {
  d: path("M24 3.5L5.92 13.336v20.816L24 44.5l18.08-10.275V13.163z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
