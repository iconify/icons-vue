<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fmry50b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-export-up-16-filled" /></template>
<style>
.fmry50b_l {
  fill: currentColor;
  d: path("M3 14.25a.75.75 0 0 1 .75-.75h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1-.75-.75m.97-9.53a.75.75 0 1 0 1.06 1.06l2.22-2.22v7.69a.75.75 0 0 0 1.5 0V3.56l2.22 2.22a.75.75 0 1 0 1.06-1.06l-3.5-3.5a.75.75 0 0 0-1.06 0z");
}

</style>
