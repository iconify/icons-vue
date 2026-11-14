<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2q1emb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basket-size" /></template>
<style>
.f2q1emb8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11h19l-2 10h-15Zm2-4.5h7V11h-7Zm8 0h7V11h-7Zm-4-4h7v4h-7ZM8 14v4m4-4v4m4-4v4");
}

</style>
