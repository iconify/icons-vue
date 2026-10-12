<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6gl-vbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:guide-dog-sharp" /></template>
<style>
.f6gl-vbio {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.35 11h9.4l.15-.58l.95-3.84L16 6l.42-.42l.66-.66l.42-.42l.47.37l.31.26q.47.37 1.01.64l1.42.71l.54.27l-.1.59l-.05.32l-.1.59l-.6.06l-1.3.13l-.6.06l-.11.59l-.53 2.82q-.11.59-.11 1.19v8.15H16l-.11-.59l-.78-4.32l-.11-.59H9l-.16.58l-1.18 4.34l-.16.58H5.75V15.6q0-.6-.15-1.18l-.7-2.84l-.15-.58zm-.6.25l-2-2.75M8.5 11l1.75-5.5m-1-2.5h5v2.5h-5z");
}

</style>
