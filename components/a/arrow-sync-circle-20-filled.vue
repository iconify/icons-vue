<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cohx4of5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sync-circle-20-filled" /></template>
<style>
.cohx4of5k {
  fill: currentColor;
  d: path("M10 18a8 8 0 1 1 0-16a8 8 0 0 1 0 16m3.5-8a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 0-1 0v.696a3.498 3.498 0 0 0-5.609-.53a.5.5 0 1 0 .746.667A2.5 2.5 0 0 1 12.293 9H11.5a.5.5 0 1 0 0 1zm-7.5.5v2a.5.5 0 0 0 1 0v-.696a3.498 3.498 0 0 0 5.609.53a.5.5 0 0 0-.745-.668A2.5 2.5 0 0 1 7.708 11H8.5a.5.5 0 0 0 0-1h-2a.5.5 0 0 0-.5.5");
}

</style>
