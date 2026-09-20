<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lybhn1bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:important-12-filled" /></template>
<style>
.lybhn1bkd {
  fill: currentColor;
  d: path("M4.283 2.98a1.735 1.735 0 1 1 3.434 0l-.576 4.03a1.153 1.153 0 0 1-2.282 0zM7 10a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

</style>
