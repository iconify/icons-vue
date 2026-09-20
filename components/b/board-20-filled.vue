<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w--22wvqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:board-20-filled" /></template>
<style>
.w--22wvqf {
  fill: currentColor;
  d: path("M9.5 3v4H3V6a3 3 0 0 1 3-3zm1 0v9H17V6a3 3 0 0 0-3-3zM17 13h-6.5v4H14a3 3 0 0 0 3-3zm-7.5 4V8H3v6a3 3 0 0 0 3 3z");
}

</style>
