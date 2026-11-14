<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o3koy_bjb"/><path class="q231xzpdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ad-extension" /></template>
<style>
.o3koy_bjb {
  d: path("M12.2 18H2.5V4h19v11.2");
}

.q231xzpdr {
  d: path("M6 7.5h5v7H6Zm8 2h4M14 13h1.2m2.8 2v6m-3-3h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
