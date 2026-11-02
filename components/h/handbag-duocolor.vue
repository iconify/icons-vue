<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ztt6nrbso"/><path class="hy34-wbrx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:handbag-duocolor" /></template>
<style>
.hy34-wbrx {
  d: path("M12 8h5c1 0 1.857.857 2 2l1 8c.133 1.062-.336 2-1 2H5c-.664 0-1.133-.938-1-2l1-8c.143-1.143 1-2 2-2z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ztt6nrbso {
  stroke-opacity: 0.4;
  d: path("M8 8a4 4 0 1 1 8 0");
}

</style>
