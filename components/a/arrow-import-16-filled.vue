<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f2tm-zbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-import-16-filled" /></template>
<style>
.f2tm-zbnc {
  fill: currentColor;
  d: path("M7.22 4.22a.75.75 0 0 1 1.06 0l3.5 3.5a.75.75 0 0 1 0 1.06l-3.5 3.5a.75.75 0 0 1-1.06-1.06L9.44 9H1.75a.75.75 0 0 1 0-1.5h7.69L7.22 5.28a.75.75 0 0 1 0-1.06m7.28-.47a.75.75 0 0 0-1.5 0v8.5a.75.75 0 0 0 1.5 0z");
}

</style>
