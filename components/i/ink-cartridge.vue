<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cf3g3irco"/><path class="hp3d2ybrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ink-cartridge" /></template>
<style>
.cf3g3irco {
  d: path("M5 2.5h14v17H5Zm5 17v2h4v-2");
}

.hp3d2ybrb {
  d: path("M12 7.5s3 3.5 3 5.5a3 3 0 0 1-6 0c0-2 3-5.5 3-5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
