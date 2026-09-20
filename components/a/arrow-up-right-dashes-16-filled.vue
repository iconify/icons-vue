<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ofvzv86ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-dashes-16-filled" /></template>
<style>
.ofvzv86ty {
  fill: currentColor;
  d: path("M7.75 2a.75.75 0 0 0 0 1.5h3.69l-1.22 1.22a.75.75 0 1 0 1.06 1.06l1.22-1.22v3.69a.75.75 0 0 0 1.5 0v-5.5a.75.75 0 0 0-.75-.75zm1.03 6.28a.75.75 0 0 0-1.06-1.06l-1.5 1.5a.75.75 0 0 0 1.06 1.06zm-4 4a.75.75 0 1 0-1.06-1.06l-1.5 1.5a.75.75 0 1 0 1.06 1.06z");
}

</style>
