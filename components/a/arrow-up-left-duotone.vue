<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="d01-lsa-n"/><path class="ulebtznia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-up-left-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d01-lsa-n {
  d: path("M168 64L64 168V64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ulebtznia {
  d: path("M197.66 186.34L127.31 116l46.35-46.34A8 8 0 0 0 168 56H64a8 8 0 0 0-8 8v104a8 8 0 0 0 13.66 5.66L116 127.31l70.34 70.35a8 8 0 0 0 11.32-11.32M72 72h76.69l-38.34 38.34L72 148.69Z");
}

</style>
