<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="oh914s7jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:grid-circles-28-regular" /></template>
<style>
.oh914s7jh {
  fill: currentColor;
  d: path("M13 8A5 5 0 1 0 3 8a5 5 0 0 0 10 0m-1.875 0a3.125 3.125 0 1 1-6.25 0a3.125 3.125 0 0 1 6.25 0M25 8a5 5 0 1 0-10 0a5 5 0 0 0 10 0m-1.875 0a3.125 3.125 0 1 1-6.25 0a3.125 3.125 0 0 1 6.25 0M8 25a5 5 0 1 1 0-10a5 5 0 0 1 0 10m0-1.875a3.125 3.125 0 1 0 0-6.25a3.125 3.125 0 0 0 0 6.25M25 20a5 5 0 1 0-10 0a5 5 0 0 0 10 0m-1.875 0a3.125 3.125 0 1 1-6.25 0a3.125 3.125 0 0 1 6.25 0");
}

</style>
