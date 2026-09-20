<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rt7g43kec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-two-split-left-20-regular" /></template>
<style>
.rt7g43kec {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm3-2a2 2 0 0 0-2 2v3.5h5.5V4zm3.5 6.5H4V14a2 2 0 0 0 2 2h3.5zM14 16a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-3.5v12z");
}

</style>
