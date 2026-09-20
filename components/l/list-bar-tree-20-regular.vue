<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dq9w8i9bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:list-bar-tree-20-regular" /></template>
<style>
.dq9w8i9bm {
  fill: currentColor;
  d: path("M5 3a2 2 0 0 0-2 2v1a2 2 0 0 0 2 2h.268A2 2 0 0 0 5 9v2c0 .597.262 1.133.677 1.5A2 2 0 0 0 5 14v1a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-1c0-.597-.262-1.133-.677-1.5c.415-.367.677-.903.677-1.5V9c0-.597-.262-1.134-.677-1.5c.415-.366.677-.903.677-1.5V5a2 2 0 0 0-2-2zm10 9h-5V8h5a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1M9 8v4H7a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1zm1 5h5a1 1 0 0 1 1 1v1a1 1 0 0 1-1 1h-5zm-1 0v3H7a1 1 0 0 1-1-1v-1a1 1 0 0 1 1-1zM8 7V4h7a1 1 0 0 1 1 1v1a1 1 0 0 1-1 1zM7 7H5a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h2z");
}

</style>
