<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="our1xplis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:exception" /></template>
<style>
.our1xplis {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.727 17.384l5.657-5.657l3.889 3.889l-5.657 5.657Zm12.465-5.535l-3.465-3.465l5.657-5.657l3.889 3.889l-5.091 5.091M8 8l2.25 2.25M18 14.5V18m0 3h.01");
}

</style>
