<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fuh-qb3dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-line-16-filled" /></template>
<style>
.fuh-qb3dp {
  fill: currentColor;
  d: path("M15 4a2 2 0 0 1-2.665 1.887l-1.64 2.05a2 2 0 0 1-2.87 2.682l-2.832 1.214q.006.075.007.151V12a2 2 0 1 1-.338-1.113l2.51-1.076a2 2 0 0 1 2.794-2.563l1.537-1.922A2 2 0 1 1 15 4");
}

</style>
