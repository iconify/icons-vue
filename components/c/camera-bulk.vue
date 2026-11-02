<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ku8s8ablc"/><path class="nsfas3bbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ku8s8ablc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 6a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h1.586l1.707-1.707C9.008 3.578 9.961 3 11 3h2c1.039 0 1.992.578 2.707 1.293L17.414 6Z");
}

.nsfas3bbb {
  d: path("M8.315 11.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m1.842 2.335a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556");
}

</style>
