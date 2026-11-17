<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rco467bop"/><path class="lirtwccvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:droplet-minus-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lirtwccvs {
  d: path("M9 13h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

.rco467bop {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.419 2.186a1 1 0 0 1 1.162 0c.404.289.787.607 1.164.93a25 25 0 0 1 2.508 2.475c.989 1.132 1.874 2.365 2.548 3.712c1.232 2.465 1.665 5.221.57 7.811a8 8 0 0 1-1.714 2.543A8 8 0 0 1 4 14c.001-3.174 1.714-6.085 3.747-8.409a25 25 0 0 1 2.508-2.475c.377-.323.76-.641 1.164-.93");
}

</style>
