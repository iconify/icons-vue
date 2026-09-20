<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c67a9rbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:magic-button-outline" /></template>
<style>
.c67a9rbpx {
  fill: currentColor;
  d: path("M10 14.175L11 12l2.175-1L11 10l-1-2.175L9 10l-2.175 1L9 12l1 2.175ZM10 19l-2.5-5.5L2 11l5.5-2.5L10 3l2.5 5.5L18 11l-5.5 2.5L10 19Zm8 2l-1.25-2.75L14 17l2.75-1.25L18 13l1.25 2.75L22 17l-2.75 1.25L18 21Zm-8-10Z");
}

</style>
