<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imd5gdbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cypress-tree-sharp" /></template>
<style>
.imd5gdbnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.86 17.99l.78-.23l.86-.26l.45-.78l.1-.19l.45-.78l-.29-.85l-.02-.05l-.29-.85l.33-.84l.04-.07l.33-.84l-.33-.84l-.04-.07l-.33-.84l.1-.87l.1-.88l-.37-.82l-.06-.11q-.37-.82-.52-1.69L14 5.25l-.56-.7l-.88-1.1l-.56-.7l-.56.7l-.88 1.1l-.56.7l-.15.88Q9.7 7 9.33 7.82l-.06.11l-.37.82l.1.88l.1.87l-.33.84l-.04.07l-.33.84l.33.84l.04.07l.33.84l-.29.85l-.02.05l-.29.85l.45.78l.1.19l.45.78l.86.26l.78.23l.86.26zm-.86.26v3m-2.5 0h5");
}

</style>
