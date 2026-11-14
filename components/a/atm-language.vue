<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e3izmxdtx"/><path class="jy45ur0ip"/><path class="u0auzh8ln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-language" /></template>
<style>
.e3izmxdtx {
  d: path("M12.9 21.5H4v-19h16v9.2");
}

.jy45ur0ip {
  d: path("M7 4.25h10v7.25H7Z");
}

.u0auzh8ln {
  d: path("M10.25 10L12 7l1.75 3M11 9h2m-6.5 5.25h5.6m-5.35 3.5h.01m2.49 0h.01m2.49 0h.01M16 14.5h4.25a1.25 1.25 0 0 1 1.25 1.25v2.5a1.25 1.25 0 0 1-1.25 1.25h-2.5l-2 1.5v-1.75c-.75-.25-1-.5-1-1v-2.5A1.25 1.25 0 0 1 16 14.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
