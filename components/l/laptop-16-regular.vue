<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jnjanvijv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-16-regular" /></template>
<style>
.jnjanvijv {
  fill: currentColor;
  d: path("M4.5 4A1.5 1.5 0 0 0 3 5.5v4A1.5 1.5 0 0 0 4.5 11h7A1.5 1.5 0 0 0 13 9.5v-4A1.5 1.5 0 0 0 11.5 4zM4 5.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-.5.5h-7a.5.5 0 0 1-.5-.5zM2.5 12a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1z");
}

</style>
