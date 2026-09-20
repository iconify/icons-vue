<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ff63g1btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bookmark-multiple-28-filled" /></template>
<style>
.ff63g1btx {
  fill: currentColor;
  d: path("M8.401 3.5A3 3 0 0 1 11 2h6.75C20.65 2 23 4.35 23 7.25V20a3 3 0 0 1-1.5 2.599V7.25a3.75 3.75 0 0 0-3.75-3.75zM5 8a3 3 0 0 1 3-3h9a3 3 0 0 1 3 3v17.25a.75.75 0 0 1-1.166.624L12.5 21.651l-6.334 4.223A.75.75 0 0 1 5 25.25z");
}

</style>
