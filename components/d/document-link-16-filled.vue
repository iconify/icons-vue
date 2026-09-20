<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="co7-62wwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-link-16-filled" /></template>
<style>
.co7-62wwb {
  fill: currentColor;
  d: path("M9 4.5V1H5.5A1.5 1.5 0 0 0 4 2.5V9h3.5a3.5 3.5 0 0 1 2.45 6h2.55a1.5 1.5 0 0 0 1.5-1.5V6h-3.5A1.5 1.5 0 0 1 9 4.5m1 0V1.25L13.75 5H10.5a.5.5 0 0 1-.5-.5M3.5 10a2.5 2.5 0 0 0 0 5H4a.5.5 0 0 0 0-1h-.5a1.5 1.5 0 0 1 0-3H4a.5.5 0 0 0 0-1zM7 10a.5.5 0 0 0 0 1h.5a1.5 1.5 0 0 1 0 3H7a.5.5 0 0 0 0 1h.5a2.5 2.5 0 0 0 0-5zm-3.5 2a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1z");
}

</style>
