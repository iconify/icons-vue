<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n6ifkxiir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-eq-16-regular" /></template>
<style>
.n6ifkxiir {
  fill: currentColor;
  d: path("M8 2a.5.5 0 0 1 .5.5v11a.5.5 0 0 1-1 0v-11A.5.5 0 0 1 8 2m2.5 2a.5.5 0 0 1 .5.5v7a.5.5 0 0 1-1 0v-7a.5.5 0 0 1 .5-.5M6 4.5a.5.5 0 0 0-1 0v7a.5.5 0 0 0 1 0zM13.5 6a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-1 0v-3a.5.5 0 0 1 .5-.5M3 6.5a.5.5 0 0 0-1 0v3a.5.5 0 0 0 1 0z");
}

</style>
