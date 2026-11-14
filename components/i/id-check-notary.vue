<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="id5kcabgz"/><path class="yijxf_bkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:id-check-notary" /></template>
<style>
.id5kcabgz {
  d: path("M12.3 19.5H2.5v-15h19v7.8m0 6.9v.3h-.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yijxf_bkk {
  d: path("M6 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1 5.5a3 3 0 0 1 6 0M14 9h4m-3.25 9l2 2L21 15.75");
}

</style>
