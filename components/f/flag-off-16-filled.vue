<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k130ilboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-off-16-filled" /></template>
<style>
.k130ilboz {
  fill: currentColor;
  d: path("m9.293 10l4.853 4.854a.5.5 0 0 0 .708-.708l-13-13a.5.5 0 1 0-.708.708L3 3.707V13.5a.5.5 0 0 0 1 0V10zM13 10h-.879l-8-8H13a.5.5 0 0 1 .407.79L11.114 6l2.293 3.21A.5.5 0 0 1 13 10");
}

</style>
