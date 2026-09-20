<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lcyy9cbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-down-right-16-regular" /></template>
<style>
.lcyy9cbbc {
  fill: currentColor;
  d: path("M10.293 4.25c.63-.63 1.707-.184 1.707.707V10.5a1.5 1.5 0 0 1-1.5 1.5H4.957c-.89 0-1.337-1.077-.707-1.707zm.707.707L4.957 11H10.5a.5.5 0 0 0 .5-.5z");
}

</style>
