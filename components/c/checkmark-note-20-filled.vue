<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xtzvuybki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-note-20-filled" /></template>
<style>
.xtzvuybki {
  fill: currentColor;
  d: path("M6.032 12.907L2.561 9.002a.75.75 0 1 0-1.122.996l4 4.5a.75.75 0 0 0 1.091.032l10.5-10.5a.75.75 0 0 0-1.06-1.06zM11 13a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2zm6.5 3h-4a.5.5 0 1 0 0 1h4a.5.5 0 1 0 0-1m-4-3a.5.5 0 1 0 0 1h4a.5.5 0 1 0 0-1z");
}

</style>
