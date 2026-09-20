<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f_k38ub-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sort-up-lines-16-filled" /></template>
<style>
.f_k38ub-k {
  fill: currentColor;
  d: path("M13 14.25a.75.75 0 0 1-1.5 0V3.56l-.72.72a.75.75 0 1 1-1.06-1.06l2-2a.75.75 0 0 1 1.06 0l2 2a.75.75 0 0 1-1.06 1.06L13 3.56zM2.75 13.5a.75.75 0 0 1 0-1.5h6.5a.75.75 0 0 1 0 1.5zm2-3a.75.75 0 0 1 0-1.5h4.5a.75.75 0 0 1 0 1.5zM6 6.75c0 .414.336.75.75.75h2.5a.75.75 0 0 0 0-1.5h-2.5a.75.75 0 0 0-.75.75");
}

</style>
