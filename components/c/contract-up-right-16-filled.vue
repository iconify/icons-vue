<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yb-48bcwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:contract-up-right-16-filled" /></template>
<style>
.yb-48bcwq {
  fill: currentColor;
  d: path("M3 4.5A1.5 1.5 0 0 1 4.5 3H8v3.5A1.5 1.5 0 0 0 9.5 8H13v3.5a1.5 1.5 0 0 1-1.5 1.5h-2a.5.5 0 0 0 0 1h2a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2h-7A2.5 2.5 0 0 0 2 4.5v2a.5.5 0 0 0 1 0zm-1 5a.5.5 0 0 0 .5.5h2.793l-3.147 3.146a.5.5 0 0 0 .708.708L6 10.707V13.5a.5.5 0 0 0 1 0v-4a.5.5 0 0 0-.5-.5h-4a.5.5 0 0 0-.5.5");
}

</style>
