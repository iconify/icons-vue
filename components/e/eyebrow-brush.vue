<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tejejfbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eyebrow-brush" /></template>
<style>
.tejejfbbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.409 11.72l2.121 2.121l-6.364 6.364l-2.121-2.121Zm8.485-6.364L11.47 12.78m5.303-8.131l2.828 2.828m-5.303-1.061l3.536 3.536m-5.657-1.414l3.535 3.535");
}

</style>
