<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vwh3l-b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-dashes-20-filled" /></template>
<style>
.vwh3l-b4e {
  fill: currentColor;
  d: path("M16.78 4.28a.75.75 0 0 0-1.06-1.06l-.5.5a.75.75 0 0 0 1.06 1.06zm-3 1.94a.75.75 0 0 1 0 1.06l-.5.5a.75.75 0 1 1-1.06-1.06l.5-.5a.75.75 0 0 1 1.06 0m-3 3a.75.75 0 0 1 0 1.06l-.5.5a.75.75 0 1 1-1.06-1.06l.5-.5a.75.75 0 0 1 1.06 0m-3 3a.75.75 0 0 1 0 1.06l-.5.5a.75.75 0 0 1-1.06-1.06l.5-.5a.75.75 0 0 1 1.06 0m-3 4.06a.75.75 0 1 0-1.06-1.06l-.5.5a.75.75 0 1 0 1.06 1.06z");
}

</style>
