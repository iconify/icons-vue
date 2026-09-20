<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vr5fov7-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-20-regular" /></template>
<style>
.vr5fov7-g {
  fill: currentColor;
  d: path("M10 2.5a.5.5 0 0 1 .5.5v6.5H17a.5.5 0 0 1 0 1h-6.5V17a.5.5 0 0 1-1 0v-6.5H3a.5.5 0 0 1 0-1h6.5V3a.5.5 0 0 1 .5-.5");
}

</style>
