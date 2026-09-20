<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="x47pdhbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-left-12-regular" /></template>
<style>
.x47pdhbjs {
  fill: currentColor;
  d: path("M10.5 6a.5.5 0 0 0-.5-.5H3.207l2.647-2.646a.5.5 0 1 0-.708-.708l-3.5 3.5a.5.5 0 0 0 0 .708l3.5 3.5a.5.5 0 0 0 .708-.708L3.207 6.5H10a.5.5 0 0 0 .5-.5");
}

</style>
