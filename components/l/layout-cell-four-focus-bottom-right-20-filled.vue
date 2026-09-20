<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cavwaebxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-cell-four-focus-bottom-right-20-filled" /></template>
<style>
.cavwaebxg {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zM4 6a2 2 0 0 1 2-2h3.5v5.5H4zm0 4.5h5.5V16H6a2 2 0 0 1-2-2zm6.5-1V4H14a2 2 0 0 1 2 2v3.5z");
}

</style>
