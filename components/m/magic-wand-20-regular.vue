<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="dyoupsb8d"/><path class="r40_4ubpm"/><path class="enuxzgbxx"/><path class="nldhrvbtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:magic-wand-20-regular" /></template>
<style>
.dyoupsb8d {
  d: path("M16.5 2a.5.5 0 0 1 .5.5V3h.5a.5.5 0 0 1 0 1H17v.5a.5.5 0 0 1-1 0V4h-.5a.5.5 0 0 1 0-1h.5v-.5a.5.5 0 0 1 .5-.5z");
  fill: currentColor;
}

.enuxzgbxx {
  d: path("M15.5 15a.5.5 0 0 0 0-1H15v-.5a.5.5 0 0 0-1 0v.5h-.5a.5.5 0 0 0 0 1h.5v.5a.5.5 0 0 0 1 0V15h.5z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.nldhrvbtb {
  d: path("M13.435 6.566a1.914 1.914 0 0 0-2.708 0l-8.166 8.166a1.914 1.914 0 1 0 2.707 2.707l8.167-8.166a1.914 1.914 0 0 0 0-2.707zm-2 .707a.914.914 0 1 1 1.292 1.293l-.477.477l-1.293-1.293l.478-.477zM10.25 8.457l1.293 1.293l-6.982 6.982a.914.914 0 0 1-1.293-1.292l6.982-6.983z");
  fill: currentColor;
}

.r40_4ubpm {
  d: path("M6.5 6a.5.5 0 1 0 0-1H6v-.5a.5.5 0 1 0-1 0V5h-.5a.5.5 0 0 0 0 1H5v.5a.5.5 0 0 0 1 0V6h.5z");
  fill: currentColor;
}

</style>
