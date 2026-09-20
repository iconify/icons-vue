<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p7t1mcczl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-32-filled" /></template>
<style>
.p7t1mcczl {
  fill: currentColor;
  d: path("M28.634 3.366a1.25 1.25 0 0 1 0 1.768l-23.5 23.5a1.25 1.25 0 0 1-1.768-1.768l23.5-23.5a1.25 1.25 0 0 1 1.768 0");
}

</style>
