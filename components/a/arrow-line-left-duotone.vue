<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="tbt519box"/><path class="cjymb0vxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-line-left-duotone" /></template>
<style>
.cjymb0vxb {
  d: path("M224 120h-72V56a8 8 0 0 0-13.66-5.66l-72 72a8 8 0 0 0 0 11.32l72 72A8 8 0 0 0 152 200v-64h72a8 8 0 0 0 0-16m-88 60.69L83.31 128L136 75.31ZM48 40v176a8 8 0 0 1-16 0V40a8 8 0 0 1 16 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.tbt519box {
  d: path("M144 56v144l-72-72Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
