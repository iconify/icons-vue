<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jfjjab6lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-vertical-scroll-20-filled" /></template>
<style>
.jfjjab6lg {
  fill: currentColor;
  d: path("M10.5 16H16a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-5.5zm-1-12H4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h5.5zm7.354 7.146a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.708 0l-2-2a.5.5 0 0 1 .708-.708l1.646 1.647l1.646-1.647a.5.5 0 0 1 .708 0m0-3a.5.5 0 0 1-.708.708L14.5 7.207l-1.646 1.647a.5.5 0 0 1-.708-.708l2-2a.5.5 0 0 1 .708 0z");
}

</style>
