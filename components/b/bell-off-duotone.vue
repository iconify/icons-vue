<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bradjz2xa"/><path class="ri7gtvjlo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-off-duotone" /></template>
<style>
.bradjz2xa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 18H6a3 3 0 0 1-3-3c0-.39.098-.773.299-1.108c.133-.222.312-.417.494-.599c.065-.066.145-.133.193-.214C4 13.057 4 13.026 4 13v-3a8 8 0 0 1 16 0v3c0 .026 0 .057.014.079c.048.081.128.148.193.214c.182.182.361.377.494.599c.201.335.299.718.299 1.108a3 3 0 0 1-3 3h-2a4 4 0 0 1-8 0");
}

.ft5dv1b6b {
  fill: none;
}

.ri7gtvjlo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H6a2 2 0 0 1-2-2c0-1 1-1 1-2v-3c0-1.678 1.015-2.794 2-4m3-3c.566-.148 1.387 0 2 0a7 7 0 0 1 7 7v2m-1 5h-6m-3 0v1a3 3 0 0 0 6 0v-1M3 2l19 19");
}

</style>
