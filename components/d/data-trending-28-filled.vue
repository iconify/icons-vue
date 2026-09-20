<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="sk3vxynpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-trending-28-filled" /></template>
<style>
.sk3vxynpp {
  fill: currentColor;
  d: path("M4 3a1 1 0 0 1 1 1v17a2 2 0 0 0 2 2h17a1 1 0 1 1 0 2H7a4 4 0 0 1-4-4V4a1 1 0 0 1 1-1m19.002 6.412V12a1 1 0 0 0 2 0V7a1 1 0 0 0-1-1h-5a1 1 0 1 0 0 2h2.584L16.5 13.086l-2.293-2.293a1 1 0 0 0-1.414 0l-5.5 5.5a1 1 0 1 0 1.414 1.414l4.793-4.793l2.293 2.293a1 1 0 0 0 1.414 0z");
}

</style>
