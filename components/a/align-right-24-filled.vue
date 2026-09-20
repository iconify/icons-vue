<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrw2v84ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-right-24-filled" /></template>
<style>
.lrw2v84ft {
  fill: currentColor;
  d: path("M21 2.75a.75.75 0 0 0-1.5 0v18.5a.75.75 0 0 0 1.5 0zM15.75 4A2.25 2.25 0 0 1 18 6.25v2.5A2.25 2.25 0 0 1 15.75 11H5.25A2.25 2.25 0 0 1 3 8.75v-2.5A2.25 2.25 0 0 1 5.25 4zm0 9A2.25 2.25 0 0 1 18 15.25v2.5A2.25 2.25 0 0 1 15.75 20h-7a2.25 2.25 0 0 1-2.25-2.25v-2.5A2.25 2.25 0 0 1 8.75 13z");
}

</style>
