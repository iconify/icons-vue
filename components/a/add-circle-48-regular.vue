<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ykup4bdvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-circle-48-regular" /></template>
<style>
.ykup4bdvw {
  fill: currentColor;
  d: path("M24 6.5C14.335 6.5 6.5 14.335 6.5 24S14.335 41.5 24 41.5S41.5 33.665 41.5 24S33.665 6.5 24 6.5M4 24C4 12.954 12.954 4 24 4s20 8.954 20 20s-8.954 20-20 20S4 35.046 4 24m20-10c.69 0 1.25.56 1.25 1.25v7.5h7.5a1.25 1.25 0 1 1 0 2.5h-7.5v7.5a1.25 1.25 0 1 1-2.5 0v-7.5h-7.5a1.25 1.25 0 1 1 0-2.5h7.5v-7.5c0-.69.56-1.25 1.25-1.25");
}

</style>
