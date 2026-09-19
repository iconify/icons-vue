<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lmgc3mwek"/><path class="qlj57ib7s"/><path class="n9xa13bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cplusplus" /></template>
<style>
.lmgc3mwek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.388 27.264a6.406 6.406 0 1 1 .116-6.745");
}

.n9xa13bam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 3.5L5.92 13.336v20.816L24 44.5l18.08-10.275V13.163zM31.818 24h3.269m-1.634-1.635v3.27M36.631 24h3.27m-1.635-1.635v3.27");
}

.qlj57ib7s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.728 30.388a11.896 11.896 0 1 1 .216-12.524m-4.44 2.656l4.44-2.656m-.216 12.524l-4.34-3.124");
}

</style>
