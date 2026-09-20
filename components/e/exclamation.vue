<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="zx2fq2bkw"/><path class="srgb_vzch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:exclamation" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.srgb_vzch {
  d: path("M12 16a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

.zx2fq2bkw {
  fill-rule: evenodd;
  d: path("M10 2a2 2 0 0 1 2 2v7a2 2 0 1 1-4 0V4a2 2 0 0 1 2-2");
}

</style>
