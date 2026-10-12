<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chh6h1bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:extension-block-sharp" /></template>
<style>
.chh6h1bok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h8v8h-8zm0 10.5h8v8h-8zm10.5 0h8v8h-8zm4.88-9.87l2.49 2.49l.88.88l-.88.88l-2.49 2.49l-.88.88l-.88-.88l-2.49-2.49l-.88-.88l.88-.88l2.49-2.49l.88-.88z");
}

</style>
