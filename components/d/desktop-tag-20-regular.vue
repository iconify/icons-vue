<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w3j436dwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-tag-20-regular" /></template>
<style>
.w3j436dwa {
  fill: currentColor;
  d: path("M15.383 11c.402 0 .789.16 1.072.447l3.108 3.14c.593.6.581 1.568-.026 2.153l-2.947 2.838a1.51 1.51 0 0 1-2.124-.031l-3.034-3.098A1.5 1.5 0 0 1 11 15.391v-2.88A1.51 1.51 0 0 1 12.51 11zM16 2a2 2 0 0 1 2 2v7.586l-.834-.842a3 3 0 0 0-.166-.152V4a1 1 0 0 0-1-1H4a1 1 0 0 0-1 1v9a1 1 0 0 0 1 1h6v1H8v2h2.585q.063.077.133.15l.833.85H5.5a.5.5 0 0 1 0-1H7v-2H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm-2.25 11a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5");
}

</style>
