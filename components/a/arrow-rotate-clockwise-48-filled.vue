<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i31jes5ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-clockwise-48-filled" /></template>
<style>
.i31jes5ff {
  fill: currentColor;
  d: path("M24 6c9.941 0 18 8.059 18 18c0 6.262-3.198 11.776-8.05 15H39a1.5 1.5 0 0 1 0 3h-8.5a1.5 1.5 0 0 1-1.5-1.5V32a1.5 1.5 0 0 1 3 0v4.688c4.206-2.658 7-7.346 7-12.688c0-8.284-6.716-15-15-15S9 15.716 9 24a1.5 1.5 0 0 1-3 0c0-9.941 8.059-18 18-18m0 12a6 6 0 1 1 0 12a6 6 0 0 1 0-12m0 3a3 3 0 1 0 0 6a3 3 0 0 0 0-6");
}

</style>
