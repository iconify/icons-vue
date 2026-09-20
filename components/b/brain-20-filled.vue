<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="as7d22tbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:brain-20-filled" /></template>
<style>
.as7d22tbs {
  fill: currentColor;
  d: path("M10.5 17.251a2.973 2.973 0 0 0 4.888-1.64l.037-.186a3.248 3.248 0 0 0 .77-6.088A2.5 2.5 0 0 0 17 7.5v-.198a2.7 2.7 0 0 0-2.169-2.646l-.406-.08l-.126-.628A2.423 2.423 0 0 0 10.5 2.462zm-1-14.79a2.423 2.423 0 0 0-3.8 1.486l-.125.628l-.406.081A2.7 2.7 0 0 0 3 7.302V7.5c0 .726.31 1.38.805 1.837a3.248 3.248 0 0 0 .77 6.088l.037.185A2.973 2.973 0 0 0 9.5 17.251z");
}

</style>
