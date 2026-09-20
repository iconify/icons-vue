<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1xjszcyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:broken-image-outline-sharp" /></template>
<style>
.l1xjszcyw {
  fill: currentColor;
  d: path("M3 21V3h18v18zm3-8.425l4-4l4 4l4-4l1 1V5H5v6.575zM5 19h14v-6.6l-1-1l-4 4l-4-4l-4 4l-1-1zm0 0v-6.6v2V5z");
}

</style>
