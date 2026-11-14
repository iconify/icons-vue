<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wj8voob3a"/><path class="v2-vfcbsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:id-verification" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v2-vfcbsx {
  d: path("M6.25 10a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM5 19c0-2.5 1.5-4 3.5-4c1.44 0 2.62.777 3.169 2.145M14.5 9.5h4m-4 3.5H17m-2.25 5l2 2L21 15.75");
}

.wj8voob3a {
  d: path("M11.8 19H2.5V5h19v7.3");
}

</style>
