<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zks-mbb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-flourescent" /></template>
<style>
.zks-mbb1u {
  fill: currentColor;
  d: path("M5 9h14v6H5zm6-7h2v3h-2zm6.286 4.399l1.79-1.803l1.42 1.41l-1.79 1.802zM11 19h2v3h-2zm6.29-1.29l1.79 1.8l1.42-1.42l-1.8-1.79zM3.495 6.01l1.407-1.408L6.69 6.391L5.284 7.798zm-.003 12.066l1.803-1.79l1.409 1.42l-1.803 1.79z");
}

</style>
