<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="byi2r8bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-right-12-regular" /></template>
<style>
.byi2r8bvp {
  fill: currentColor;
  d: path("M4 3.994c0-.887 1.07-1.335 1.702-.712l2.037 2.006a1 1 0 0 1 0 1.425L5.702 8.719C5.069 9.34 4 8.893 4 8.006zM7.037 6L5 3.994v4.012z");
}

</style>
