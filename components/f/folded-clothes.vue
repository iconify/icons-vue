<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rr2_eznqp"/><path class="zwjedjblj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:folded-clothes" /></template>
<style>
.rr2_eznqp {
  d: path("M3.5 4.5h17v16h-17Zm0 6h17m-17 5h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwjedjblj {
  d: path("m9 4.5l3 3l3-3");
}

</style>
