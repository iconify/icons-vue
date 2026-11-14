<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lgbkgy7xs"/><path class="ztg9kcctx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gene-therapy" /></template>
<style>
.lgbkgy7xs {
  d: path("M6 2.5c0 4 7 5 7 9.5s-7 5.5-7 9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ztg9kcctx {
  d: path("M13 2.5c0 4-7 5-7 9.5c0 3.411 4.021 4.811 5.968 7.03M7.75 4h3.5m-3.5 8h3.5m-3.5 8h3.3m8.011-5.828l1.767 1.767l-3.889 3.889l-1.767-1.767Zm-3.006 4.773l-1.591 1.591m4.243-6.718l2.475 2.475");
}

</style>
