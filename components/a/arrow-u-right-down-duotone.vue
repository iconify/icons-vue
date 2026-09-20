<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vsebzacqg"/><path class="r5ax09ssl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-right-down-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r5ax09ssl {
  d: path("M223.39 172.94A8 8 0 0 0 216 168h-40V88a64 64 0 0 0-128 0v88a8 8 0 0 0 16 0V88a48 48 0 0 1 96 0v80h-40a8 8 0 0 0-5.66 13.66l48 48a8 8 0 0 0 11.32 0l48-48a8 8 0 0 0 1.73-8.72M168 212.69L139.31 184h57.38Z");
}

.vsebzacqg {
  d: path("m216 176l-48 48l-48-48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
