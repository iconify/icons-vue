<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hcv3fzj1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bluetooth-32-regular" /></template>
<style>
.hcv3fzj1n {
  fill: currentColor;
  d: path("M15.6 2.083a1 1 0 0 1 1.08.184l7 6.5a1 1 0 0 1 0 1.466L17.47 16l6.21 5.767a1 1 0 0 1 0 1.466l-7 6.5A1 1 0 0 1 15 29V18.293l-5.32 4.94a1 1 0 1 1-1.36-1.466L14.53 16l-6.21-5.767a1 1 0 0 1 1.36-1.466l5.32 4.94V3a1 1 0 0 1 .6-.917m1.4 16.21v8.414l4.53-4.207zm0-4.586L21.53 9.5L17 5.293z");
}

</style>
