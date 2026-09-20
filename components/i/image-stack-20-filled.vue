<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xnajin0nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-stack-20-filled" /></template>
<style>
.xnajin0nq {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v3h3.293l2.47-2.47a1.75 1.75 0 0 1 2.474 0L13.707 9H17V6a3 3 0 0 0-3-3zm11 7v4a3 3 0 0 1-2.361 2.932l-3.402-3.402a1.75 1.75 0 0 0-2.474 0L5.36 16.932A3 3 0 0 1 3 14v-4zM6.707 17h6.586l-2.763-2.763a.75.75 0 0 0-1.06 0zm1-8h4.586L10.53 7.237a.75.75 0 0 0-1.06 0zM15.5 5.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-1 8a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
