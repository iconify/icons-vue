<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wlgxvc3yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-two-split-right-focus-left-20-filled" /></template>
<style>
.wlgxvc3yd {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm7-2v5.5h6V6a2 2 0 0 0-2-2zm0 6.5V16h4a2 2 0 0 0 2-2v-3.5z");
}

</style>
