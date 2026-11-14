<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj0nhoxaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dojo-door" /></template>
<style>
.wj0nhoxaz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 8l3.5-4.5h11L21 8Zm1 0v13.5h16V8m-8 0v13.5M9.25 13v3.5m5.5-3.5v3.5");
}

</style>
