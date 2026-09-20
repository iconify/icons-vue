<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="h2qz3l81b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-import-28-filled" /></template>
<style>
.h2qz3l81b {
  fill: currentColor;
  d: path("M25 5a1 1 0 0 1 1 1v16a1 1 0 1 1-2 0V6a1 1 0 0 1 1-1M13.793 6.793a1 1 0 0 1 1.414 0l6.5 6.5a1 1 0 0 1 0 1.414l-6.5 6.5a1 1 0 1 1-1.414-1.414L18.586 15H3a1 1 0 1 1 0-2h15.586l-4.793-4.793a1 1 0 0 1 0-1.414");
}

</style>
