<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xq2qjlr5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dock-left-20-filled" /></template>
<style>
.xq2qjlr5h {
  d: path("M16 4a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2zm0 1H8v10h8a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1z");
  fill: currentColor;
  fill-rule: nonzero;
}

</style>
