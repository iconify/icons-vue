<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yh3btko3l"/><path clip-rule="evenodd" class="dgy411bol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-single-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dgy411bol {
  fill-rule: evenodd;
  d: path("M3 20L3 11C3 10.4477 3.4477 10 4 10L20 10C20.5523 10 21 10.4477 21 11L21 20C21 20.5523 20.5523 21 20 21L4 21C3.4477 21 3 20.5523 3 20ZM5 12L5 14L19 14L19 12L5 12Z");
}

.yh3btko3l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 20L3 11C3 10.4477 3.4477 10 4 10L6 10L6 4C6 3.4477 6.4477 3 7 3L17 3C17.5523 3 18 3.4477 18 4L18 10L20 10C20.5523 10 21 10.4477 21 11L21 20C21 20.5523 20.5523 21 20 21L4 21C3.4477 21 3 20.5523 3 20Z");
}

</style>
