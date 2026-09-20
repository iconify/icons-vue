<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gejj4lj6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-fork-20-filled" /></template>
<style>
.gejj4lj6r {
  fill: currentColor;
  d: path("M9 5a3 3 0 0 1-2.5 2.959V10H12a1.5 1.5 0 0 0 1.5-1.5v-.541a3 3 0 1 1 1 0V8.5A2.5 2.5 0 0 1 12 11H6.5v1.041a3 3 0 1 1-1 0V7.96A3 3 0 1 1 9 5");
}

</style>
