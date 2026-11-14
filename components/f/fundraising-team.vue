<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jykdeph6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fundraising-team" /></template>
<style>
.jykdeph6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM6.5 19.5c0-2.038.848-3.738 2.149-4.801m.403-.3A5.26 5.26 0 0 1 12 13.5c.549 0 1.082.084 1.585.242M6 10a2.5 2.5 0 0 1 0-5M2.5 18c0-2 1-3.5 2.5-4m12.75 0l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
