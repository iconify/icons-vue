<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns5yu1bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dismiss-square-24-filled" /></template>
<style>
.ns5yu1bsa {
  fill: currentColor;
  d: path("M6.25 3A3.25 3.25 0 0 0 3 6.25v11.5A3.25 3.25 0 0 0 6.25 21h11.5A3.25 3.25 0 0 0 21 17.75V6.25A3.25 3.25 0 0 0 17.75 3zm1.97 5.22a.75.75 0 0 1 1.06 0L12 10.94l2.72-2.72a.75.75 0 1 1 1.06 1.06L13.06 12l2.72 2.72a.75.75 0 1 1-1.06 1.06L12 13.06l-2.72 2.72a.75.75 0 0 1-1.06-1.06L10.94 12L8.22 9.28a.75.75 0 0 1 0-1.06");
}

</style>
