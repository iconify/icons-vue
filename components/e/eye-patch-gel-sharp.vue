<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bilzntutq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eye-patch-gel-sharp" /></template>
<style>
.bilzntutq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 6.5c1.9 2 4.6 3 6 3s4.1-1 6-3m-9.75 2L7.5 10m4.5-.5v1.75m3.75-2.75l.75 1.5M4.25 12.5c2.2 1.6 5 2.5 7.75 2.5s5.55-.9 7.75-2.5c.6 3.9-3.3 7.75-7.75 7.75S3.65 16.4 4.25 12.5Z");
}

</style>
