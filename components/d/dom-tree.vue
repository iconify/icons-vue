<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1ck_us3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dom-tree" /></template>
<style>
.u1ck_us3i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 1.75h2q3.25 0 3.25 3.25T7 8.25h-.25v2.25h5.054q.348-2.25 2.946-2.25h4.5q3 0 3 3t-3 3h-4.5q-2.598 0-2.946-2.25H6.75v6h5.054q.348-2.25 2.946-2.25h4.5q3 0 3 3t-3 3h-4.5q-2.598 0-2.946-2.25H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V8.25H5Q1.75 8.25 1.75 5q0-1.346.952-2.298T5 1.75");
}

</style>
