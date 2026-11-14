<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4_gqibbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:author-signing" /></template>
<style>
.n4_gqibbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h6A3.5 3.5 0 0 1 12 7v11.5A2.5 2.5 0 0 0 9.5 16h-7Zm19 8.584V3.5h-6q-.172 0-.343.017t-.34.05q-.168.034-.333.084t-.323.115q-.159.066-.311.147t-.294.177q-.143.095-.276.204q-.133.11-.255.231q-.121.122-.231.255q-.109.133-.204.276q-.096.142-.177.294t-.147.311q-.065.158-.115.323t-.084.333t-.05.34T12 7v11.5q0-.108.009-.216q.01-.108.028-.215q.019-.106.047-.211t.064-.207t.083-.2q.045-.098.099-.192t.115-.183t.131-.173q.069-.083.145-.16q.077-.077.159-.147q.083-.07.171-.133t.181-.118t.192-.101q.097-.047.199-.085q.101-.038.205-.067q.105-.029.211-.049m.711 5.457l.5-2.75l4.5-4.5L22 16.5L17.5 21Z");
}

</style>
