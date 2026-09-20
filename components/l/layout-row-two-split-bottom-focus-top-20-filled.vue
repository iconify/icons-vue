<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="np369qzta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-split-bottom-focus-top-20-filled" /></template>
<style>
.np369qzta {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm13 4h-5.5v6H14a2 2 0 0 0 2-2zm-6.5 0H4v4a2 2 0 0 0 2 2h3.5z");
}

</style>
