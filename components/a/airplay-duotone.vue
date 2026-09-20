<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="hqc2lwb3c"/><path class="mclqp3b9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:airplay-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hqc2lwb3c {
  d: path("M224 64v112a16 16 0 0 1-16 16h-52.57L128 160l-27.43 32H48a16 16 0 0 1-16-16V64a16 16 0 0 1 16-16h160a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mclqp3b9m {
  d: path("M134.08 154.79a8 8 0 0 0-12.15 0l-48 56A8 8 0 0 0 80 224h96a8 8 0 0 0 6.07-13.21ZM97.39 208L128 172.29L158.61 208ZM232 64v112a24 24 0 0 1-24 24h-8a8 8 0 0 1 0-16h8a8 8 0 0 0 8-8V64a8 8 0 0 0-8-8H48a8 8 0 0 0-8 8v112a8 8 0 0 0 8 8h8a8 8 0 0 1 0 16h-8a24 24 0 0 1-24-24V64a24 24 0 0 1 24-24h160a24 24 0 0 1 24 24");
}

</style>
