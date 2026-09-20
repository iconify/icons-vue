<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v2jdjzblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dock-panel-right-20-regular" /></template>
<style>
.v2jdjzblf {
  fill: currentColor;
  d: path("M18 6a3 3 0 0 0-3-3H5a3 3 0 0 0-3 3v7a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3zm-6.5-2v11H5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2zm1 0H15a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-2.5z");
}

</style>
