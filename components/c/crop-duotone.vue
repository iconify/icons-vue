<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="kzooy8bcn"/><path class="e3oqakbxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:crop-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e3oqakbxm {
  d: path("M240 192a8 8 0 0 1-8 8h-32v32a8 8 0 0 1-16 0v-32H64a8 8 0 0 1-8-8V72H24a8 8 0 0 1 0-16h32V24a8 8 0 0 1 16 0v160h160a8 8 0 0 1 8 8M96 72h88v88a8 8 0 0 0 16 0V64a8 8 0 0 0-8-8H96a8 8 0 0 0 0 16");
}

.kzooy8bcn {
  d: path("M192 64v128H64V64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
