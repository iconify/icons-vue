<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc__b3b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:epinephrine-injector" /></template>
<style>
.yc__b3b4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.399 16.419l12.02-12.02l3.182 3.182l-12.02 12.02Zm8.485-8.485l3.182 3.182m-8.132 1.768l3.182 3.182M9.348 11.47l3.182 3.182m-8.485 3.889l1.237-1.238l1.415 1.415l-1.238 1.237Z");
}

</style>
