<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e99osqbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-fork-16-filled" /></template>
<style>
.e99osqbei {
  fill: currentColor;
  d: path("M7 3.5a2.5 2.5 0 0 1-2 2.45V8h4.5A1.5 1.5 0 0 0 11 6.5v-.55a2.5 2.5 0 1 1 1 0v.55A2.5 2.5 0 0 1 9.5 9H5v1.05a2.5 2.5 0 1 1-1 0v-4.1A2.5 2.5 0 1 1 7 3.5");
}

</style>
