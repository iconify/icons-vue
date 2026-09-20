<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zy00o9bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:channel-add-16-filled" /></template>
<style>
.zy00o9bux {
  fill: currentColor;
  d: path("M1.63 2.29q.18-.04.37-.04a1.75 1.75 0 1 1-.5 3.428V8a2 2 0 0 0 2 2h1.522A5.5 5.5 0 0 1 10.5 5V3a2 2 0 0 0-2-2h-5a2 2 0 0 0-1.87 1.29M4 4.5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 0 1h-3a.5.5 0 0 1-.5-.5M4.5 7a.5.5 0 0 1 0-1H6a.5.5 0 0 1 0 1zM2.75 4a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0M15 10.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V10H8.5a.5.5 0 0 0 0 1H10v1.5a.5.5 0 0 0 1 0V11h1.5a.5.5 0 0 0 0-1H11z");
}

</style>
