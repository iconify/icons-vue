<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i46hy3bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clock-bill-16-regular" /></template>
<style>
.i46hy3bvh {
  fill: currentColor;
  d: path("M16 7a7 7 0 0 1-7 7v-1a6 6 0 1 0-5.918-7H2.07A7.002 7.002 0 0 1 16 7m-8-.236c.371.332.66.756.829 1.236h2.67a.5.5 0 1 0 0-1H9V3.5a.5.5 0 1 0-1 0zM0 9a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2zm5.5 0h-3a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1m0 2h-3a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1m0 2h-3a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1");
}

</style>
