<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p-equeigw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:building-government-search-32-filled" /></template>
<style>
.p-equeigw {
  fill: currentColor;
  d: path("M16 2h4.667c.368 0 .666.298.666.667v2.666a.667.667 0 0 1-.666.667H17v1.055A9 9 0 0 1 25 16h2a3 3 0 0 1 3 3v9a1 1 0 0 1-1 1H19v-4a1 1 0 0 0-1-1h-3.65q.149-.729.15-1.5a7.47 7.47 0 0 0-1.76-4.827A1 1 0 0 0 13 17v-3a1 1 0 1 0-2 0v2.155A7.46 7.46 0 0 0 7.055 15A9.004 9.004 0 0 1 15 7.055V3a1 1 0 0 1 1-1m5 12a1 1 0 1 0-2 0v3a1 1 0 1 0 2 0zm-4 3v-3a1 1 0 1 0-2 0v3a1 1 0 1 0 2 0m8 4a1 1 0 1 0-2 0v3a1 1 0 0 0 2 0zM7 28.5c1.296 0 2.496-.41 3.476-1.11l3.317 3.317a1 1 0 0 0 1.414-1.414l-3.316-3.316A6 6 0 1 0 7 28.5m0-2a4 4 0 1 1 0-8a4 4 0 0 1 0 8");
}

</style>
