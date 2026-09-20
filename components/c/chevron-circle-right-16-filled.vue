<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o88pmhbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-right-16-filled" /></template>
<style>
.o88pmhbun {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m-.646 3.646a.5.5 0 1 0-.708.708L9.293 8l-2.647 2.646a.5.5 0 1 0 .708.707l3-3a.5.5 0 0 0 0-.707z");
}

</style>
