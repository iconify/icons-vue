<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gwwr9x_vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-dashes-20-regular" /></template>
<style>
.gwwr9x_vx {
  fill: currentColor;
  d: path("M16.854 3.854a.5.5 0 0 0-.708-.708l-1 1a.5.5 0 0 0 .708.708zm-3 2.292a.5.5 0 0 1 0 .708l-1 1a.5.5 0 0 1-.708-.708l1-1a.5.5 0 0 1 .708 0m-3 3a.5.5 0 0 1 0 .708l-1 1a.5.5 0 0 1-.708-.708l1-1a.5.5 0 0 1 .708 0m-3 3a.5.5 0 0 1 0 .708l-1 1a.5.5 0 0 1-.708-.708l1-1a.5.5 0 0 1 .708 0m-3 3.708a.5.5 0 0 0-.708-.708l-1 1a.5.5 0 0 0 .708.708z");
}

</style>
