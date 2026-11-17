<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rco467bop"/><path class="fs9m27bcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:droplet-percent-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fs9m27bcc {
  d: path("M10.707 16.707a.999.999 0 1 1-1.414-1.414l4-4a.999.999 0 1 1 1.414 1.414ZM10.01 11a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2ZM14 15h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2");
}

.rco467bop {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.419 2.186a1 1 0 0 1 1.162 0c.404.289.787.607 1.164.93a25 25 0 0 1 2.508 2.475c.989 1.132 1.874 2.365 2.548 3.712c1.232 2.465 1.665 5.221.57 7.811a8 8 0 0 1-1.714 2.543A8 8 0 0 1 4 14c.001-3.174 1.714-6.085 3.747-8.409a25 25 0 0 1 2.508-2.475c.377-.323.76-.641 1.164-.93");
}

</style>
