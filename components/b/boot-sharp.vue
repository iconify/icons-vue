<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhqn-kzec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:boot-sharp" /></template>
<style>
.zhqn-kzec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.75h7.25v9.75l5.15 1.9l2.599 1.056l.251 2.794H4.5Zm3.75 3.5h3.5m-3.5 3h3.5m-7.25 9h15.25v3H4.5z");
}

</style>
