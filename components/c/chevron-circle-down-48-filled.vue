<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n9a9_3mix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-down-48-filled" /></template>
<style>
.n9a9_3mix {
  fill: currentColor;
  d: path("M24 44c11.046 0 20-8.954 20-20S35.046 4 24 4S4 12.954 4 24s8.954 20 20 20m-8.616-23.634L24 28.982l8.616-8.616a1.25 1.25 0 0 1 1.768 1.768l-9.5 9.5a1.25 1.25 0 0 1-1.768 0l-9.5-9.5a1.25 1.25 0 0 1 1.768-1.768");
}

</style>
