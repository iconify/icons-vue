<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fepf0accp"/><path class="qzzct-bwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:info" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fepf0accp {
  fill-rule: evenodd;
  d: path("M10 7a2 2 0 0 1 2 2v7a2 2 0 1 1-4 0V9a2 2 0 0 1 2-2");
}

.qzzct-bwg {
  d: path("M12 4a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

</style>
