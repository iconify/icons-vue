<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="esgopmbqm"/><path class="o676k8b2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cell-signal-x-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.esgopmbqm {
  d: path("M200 40v120l-45.66 45.66a8 8 0 0 1-5.65 2.34H32a8 8 0 0 1-5.66-13.66l160-160A8 8 0 0 1 200 40");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o676k8b2p {
  d: path("M213.66 194.34a8 8 0 0 1-11.32 11.32L184 187.31l-18.35 18.35a8 8 0 0 1-11.31-11.32L172.68 176l-18.34-18.35a8 8 0 0 1 11.31-11.31L184 164.68l18.34-18.34a8 8 0 0 1 11.32 11.31L195.31 176ZM120 200H32L192 40v72a8 8 0 0 0 16 0V40a16 16 0 0 0-27.31-11.32l-160 160A16 16 0 0 0 32 216h88a8 8 0 0 0 0-16");
}

</style>
