<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ge7p804hb"/><path class="a3_n9nbvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:magazine-spread" /></template>
<style>
.a3_n9nbvt {
  d: path("M14.75 8.5h4v4h-4Zm0 7h4");
}

.ge7p804hb {
  d: path("M2.5 5H10l2 1.5L14 5h7.5v14H14l-2 1.5l-2-1.5H2.5ZM12 6.5v14m-6.75-11h4m-4 4h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
