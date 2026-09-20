<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhz8apicj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:highway-24-regular" /></template>
<style>
.uhz8apicj {
  fill: currentColor;
  d: path("M7.49 2.87a.75.75 0 1 0-1.48-.24l-3 18.5a.75.75 0 1 0 1.48.24zm10.5-.24a.75.75 0 1 0-1.48.24l3 18.5a.75.75 0 1 0 1.48-.24zm-5.24.12a.75.75 0 0 0-1.5 0v3.5a.75.75 0 0 0 1.5 0zm-1.5 11a.75.75 0 0 0 1.5 0v-3.5a.75.75 0 0 0-1.5 0zm0 4a.75.75 0 0 1 1.5 0v3.5a.75.75 0 0 1-1.5 0z");
}

</style>
