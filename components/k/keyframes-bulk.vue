<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lhu51pbnn"/><path class="vrb0-gbcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:keyframes-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lhu51pbnn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m13.707 8.293l2 2a2.414 2.414 0 0 1 0 3.414l-2 2a2.414 2.414 0 0 1-3.414 0l-2-2a2.414 2.414 0 0 1 0-3.414l2-2a2.414 2.414 0 0 1 3.414 0");
}

.vrb0-gbcf {
  d: path("m5.707 9.707l-2 2a.414.414 0 0 0 0 .586l2 2a.999.999 0 1 1-1.414 1.414l-2-2a2.414 2.414 0 0 1 0-3.414l2-2a.999.999 0 1 1 1.414 1.414m14-1.414l2 2a2.414 2.414 0 0 1 0 3.414l-2 2a1 1 0 0 1-1.414-1.414l2-2a.414.414 0 0 0 0-.586l-2-2a1 1 0 0 1 1.414-1.414");
}

</style>
