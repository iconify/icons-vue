<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="una344b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-circle-20-regular" /></template>
<style>
.una344b8v {
  fill: currentColor;
  d: path("M6 10a.5.5 0 0 1 .5-.5h3v-3a.5.5 0 0 1 1 0v3h3a.5.5 0 0 1 0 1h-3v3a.5.5 0 0 1-1 0v-3h-3A.5.5 0 0 1 6 10m4 8a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-1a7 7 0 1 1 0-14a7 7 0 0 1 0 14");
}

</style>
