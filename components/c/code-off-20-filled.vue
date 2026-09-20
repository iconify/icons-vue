<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fa4ap1bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-off-20-filled" /></template>
<style>
.fa4ap1bgk {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .707 0l15 15a.5.5 0 0 1-.707.708l-7.141-7.142l-2.569 5.84a.75.75 0 0 1-1.373-.604l2.803-6.375l-2.87-2.87a.74.74 0 0 1-.151.505L3.696 10l2.149 2.793a.75.75 0 0 1-1.19.915l-2.5-3.25a.75.75 0 0 1 0-.915l2.5-3.25a.75.75 0 0 1 .64-.291L2.146 2.854a.5.5 0 0 1 0-.708m12.147 4.01a.75.75 0 0 1 1.052.137l2.5 3.25a.75.75 0 0 1 0 .915l-2.29 2.976l-1.07-1.07L16.303 10l-2.149-2.792a.75.75 0 0 1 .138-1.052m-2.73-2.708a.751.751 0 0 1 1.374.605L10.87 8.749L9.731 7.61z");
}

</style>
