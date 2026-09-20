<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g8cmf_gmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-20-filled" /></template>
<style>
.g8cmf_gmi {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 0-2 2v1h15v8.5a.5.5 0 0 0 1 0V6a2 2 0 0 0-2-2zm6 4H2v6a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2zm-5.5 2.5A.5.5 0 0 1 5 10h2a.5.5 0 0 1 0 1H5a.5.5 0 0 1-.5-.5");
}

</style>
