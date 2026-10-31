<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uzami2ila"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-20-filled" /></template>
<style>
.uzami2ila {
  fill: currentColor;
  d: path("M7 11a4 4 0 0 0 4 4h1a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h2zm8-9a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3z");
}

</style>
