<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z_s5q9opl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:call-chevron-down-48-filled" /></template>
<style>
.z_s5q9opl {
  fill: currentColor;
  d: path("M14.162 3.75a5.25 5.25 0 0 1 4.955 3.516l1.572 4.489a5.25 5.25 0 0 1-1.904 6.007l-2.767 1.975c-.812.58-1.022 1.344-.792 1.904c1.008 2.45 3.301 5.758 5.16 7.674c.454.468 1.224.63 2.07.32l2.958-1.085a5.25 5.25 0 0 1 5.853 1.582l2.414 2.918a5.17 5.17 0 0 1 .428 5.987c-2.637 4.315-8.15 6.451-12.643 3.377A40 40 0 0 1 9.418 29.375c-3.67-6.356-4.744-12.384-4.879-16.89c-.16-5.355 4.54-8.735 9.47-8.735zm27.454 6.616a1.25 1.25 0 1 1 1.768 1.768l-7.5 7.5a1.25 1.25 0 0 1-1.768 0l-7.5-7.5a1.25 1.25 0 0 1 1.768-1.768L35 16.982z");
}

</style>
