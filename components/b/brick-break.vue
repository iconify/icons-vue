<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j6mh-y6ky"/><path class="odoruzb7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brick-break" /></template>
<style>
.j6mh-y6ky {
  d: path("M3 3.5h15V9h3v5.5h-3V20H3v-5.5h3V9H3ZM6 9h12M6 14.5h12");
}

.odoruzb7a {
  d: path("m9 3.5l2.5 3L10 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
