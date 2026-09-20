<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s3z99nbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-dynamic-20-filled" /></template>
<style>
.s3z99nbme {
  fill: currentColor;
  d: path("M7 17H6a3 3 0 0 1-3-3v-1h4zm10-3a3 3 0 0 1-3 3H8v-4h9zM7 12H3V6a3 3 0 0 1 3-3h1zm7-9a3 3 0 0 1 3 3v6H8V3z");
}

</style>
