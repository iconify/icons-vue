<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p4ifodbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-right-16-regular" /></template>
<style>
.p4ifodbjc {
  fill: currentColor;
  d: path("M7.571 11.84C6.908 12.298 6 11.827 6 11.024V4.975c0-.803.908-1.274 1.571-.816l3.784 2.617a1.486 1.486 0 0 1 0 2.447zM7 11.024l3.784-2.617a.495.495 0 0 0 0-.815L7 4.975z");
}

</style>
