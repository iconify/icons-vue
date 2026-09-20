<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eq7p-wbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sort-down-line-20-filled" /></template>
<style>
.eq7p-wbbb {
  fill: currentColor;
  d: path("M15 2.75a.75.75 0 0 0-1.5 0v12.572l-1.447-1.579a.75.75 0 0 0-1.106 1.014l2.75 3a.75.75 0 0 0 1.106 0l2.75-3a.75.75 0 0 0-1.106-1.014L15 15.322zM2.75 3.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5zM5 7.25a.75.75 0 0 1 .75-.75h5.5a.75.75 0 0 1 0 1.5h-5.5A.75.75 0 0 1 5 7.25M8.75 9.5a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5z");
}

</style>
