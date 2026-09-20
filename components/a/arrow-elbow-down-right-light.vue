<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xhagcebtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-elbow-down-right-light" /></template>
<style>
.xhagcebtn {
  fill: currentColor;
  d: path("m220.24 180.24l-48 48a6 6 0 0 1-8.48-8.48L201.51 182H72a6 6 0 0 1-6-6V32a6 6 0 0 1 12 0v138h123.51l-37.75-37.76a6 6 0 1 1 8.48-8.48l48 48a6 6 0 0 1 0 8.48");
}

</style>
