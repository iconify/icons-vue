<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cvlt-54sb"/><path class="t6vdoacwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dowel-pin" /></template>
<style>
.cvlt-54sb {
  d: path("M2.5 13h19v8.5h-19Z");
}

.t6vdoacwd {
  d: path("M9.5 17.5v-12l1.5-2h2l1.5 2v12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
