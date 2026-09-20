<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f8j5y1bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-circle-48-regular" /></template>
<style>
.f8j5y1bks {
  fill: currentColor;
  d: path("M24 4c11.046 0 20 8.954 20 20s-8.954 20-20 20S4 35.046 4 24S12.954 4 24 4m0 2.5C14.335 6.5 6.5 14.335 6.5 24S14.335 41.5 24 41.5S41.5 33.665 41.5 24S33.665 6.5 24 6.5m8.634 11.116a1.25 1.25 0 0 1 0 1.768l-11 11a1.25 1.25 0 0 1-1.768 0l-4.5-4.5a1.25 1.25 0 0 1 1.768-1.768l3.616 3.616l10.116-10.116a1.25 1.25 0 0 1 1.768 0");
}

</style>
