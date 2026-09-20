<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y3-hd-tsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:badge-20-regular" /></template>
<style>
.y3-hd-tsh {
  fill: currentColor;
  d: path("M16 6a2 2 0 1 0 0-4a2 2 0 0 0 0 4m1 9V6.83c-.313.11-.65.17-1 .17v8a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h8c0-.35.06-.687.17-1H5a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2");
}

</style>
