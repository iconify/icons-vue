<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="typlp7f1a"/><path class="f8ecqdbrx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donate-bicycle" /></template>
<style>
.f8ecqdbrx {
  d: path("M5.5 12h6L16 5.5l2.439 6.341M9 4.5h3m-1.5 0l1 7.5M16 5.5l-1-2h-1.5m1.5 13h6v5h-6Zm1-2.25l2 2.25l2-2.25m-2 2.25v5");
}

.typlp7f1a {
  d: path("M2 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm19.987.296Q22 12.148 22 12q0-.172-.017-.343t-.05-.34q-.034-.168-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294t-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05T18.5 8.5q-.153 0-.306.013q-.152.014-.303.04t-.299.067q-.147.039-.291.092q-.144.052-.283.117t-.271.142t-.258.164t-.242.187q-.117.098-.226.207q-.108.108-.206.226q-.098.117-.186.243q-.087.125-.164.258q-.076.133-.14.272t-.117.283t-.091.292t-.065.298");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
