<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfaw_mbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:edit-lock" /></template>
<style>
.bfaw_mbqx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.243 3.929l2.828 2.828L8 13.828l-3.536.708L5.172 11ZM15.5 16h6v4.5h-6Zm1.25 0v-1.25a1.75 1.75 0 0 1 3.5 0V16");
}

</style>
