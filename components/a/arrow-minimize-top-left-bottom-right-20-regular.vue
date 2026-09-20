<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k5f2-qb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-minimize-top-left-bottom-right-20-regular" /></template>
<style>
.k5f2-qb8s {
  fill: currentColor;
  d: path("M16.5 11a.5.5 0 0 1 0 1h-3.793l5.147 5.147a.5.5 0 0 1-.707.707L12 12.707V16.5a.5.5 0 1 1-1 0v-5a.5.5 0 0 1 .5-.5zM2.146 2.147a.5.5 0 0 1 .707 0L8 7.293V3.5a.5.5 0 1 1 1 0v5a.5.5 0 0 1-.5.5h-5a.5.5 0 0 1 0-1h3.793L2.146 2.854a.5.5 0 0 1 0-.707");
}

</style>
