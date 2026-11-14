<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mpy7sqbxz"/><path class="aclrasbzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beam-lift" /></template>
<style>
.aclrasbzs {
  d: path("M12 6v1.5A2.5 2.5 0 1 1 9.5 10");
}

.mpy7sqbxz {
  d: path("M2.5 15.5h19v5h-19Zm2 0l7.5-3l7.5 3m-9.75-13h4.5V6h-4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
