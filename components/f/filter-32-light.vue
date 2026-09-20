<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e8ow0mb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filter-32-light" /></template>
<style>
.e8ow0mb1l {
  fill: currentColor;
  d: path("M3 8.5a.5.5 0 0 1 .5-.5h25a.5.5 0 0 1 0 1h-25a.5.5 0 0 1-.5-.5m4 7a.5.5 0 0 1 .5-.5h17a.5.5 0 0 1 0 1h-17a.5.5 0 0 1-.5-.5m4.5 6.5a.5.5 0 0 0 0 1h9a.5.5 0 0 0 0-1z");
}

</style>
