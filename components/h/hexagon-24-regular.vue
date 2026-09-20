<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahyn6x90y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hexagon-24-regular" /></template>
<style>
.ahyn6x90y {
  fill: currentColor;
  d: path("M6.157 4.125A2.25 2.25 0 0 1 8.105 3h7.79a2.25 2.25 0 0 1 1.95 1.125l3.895 6.75a2.25 2.25 0 0 1 0 2.25l-3.896 6.75A2.25 2.25 0 0 1 15.895 21h-7.79a2.25 2.25 0 0 1-1.948-1.125l-3.896-6.75a2.25 2.25 0 0 1 0-2.25zm1.948.375a.75.75 0 0 0-.65.375l-3.895 6.75a.75.75 0 0 0 0 .75l3.896 6.75a.75.75 0 0 0 .65.375h7.79a.75.75 0 0 0 .649-.375l3.895-6.75a.75.75 0 0 0 0-.75l-3.895-6.75a.75.75 0 0 0-.65-.375z");
}

</style>
