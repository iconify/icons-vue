<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ngdojo--z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-two-16-filled" /></template>
<style>
.ngdojo--z {
  fill: currentColor;
  d: path("M8.5 14h3a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2h-3zm-1-12h-3A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14h3z");
}

</style>
