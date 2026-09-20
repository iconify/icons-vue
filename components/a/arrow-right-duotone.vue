<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vcs-xzb2n"/><path class="wb-y47q2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-right-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vcs-xzb2n {
  d: path("m216 128l-72 72V56Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wb-y47q2f {
  d: path("m221.66 122.34l-72-72A8 8 0 0 0 136 56v64H40a8 8 0 0 0 0 16h96v64a8 8 0 0 0 13.66 5.66l72-72a8 8 0 0 0 0-11.32M152 180.69V75.31L204.69 128Z");
}

</style>
