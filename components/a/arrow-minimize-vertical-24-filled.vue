<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awejaf12y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-minimize-vertical-24-filled" /></template>
<style>
.awejaf12y {
  fill: currentColor;
  d: path("M13.793 18.707a1 1 0 1 0 1.414-1.414l-2.5-2.5a1 1 0 0 0-1.414 0l-2.5 2.5a1 1 0 1 0 1.414 1.414l.793-.793V21a1 1 0 1 0 2 0v-3.086zM4 12a1 1 0 0 1 1-1h14a1 1 0 1 1 0 2H5a1 1 0 0 1-1-1m9-9a1 1 0 1 0-2 0v3.086l-.793-.793a1 1 0 0 0-1.414 1.414l2.5 2.5a1 1 0 0 0 1.414 0l2.5-2.5a1 1 0 0 0-1.414-1.414L13 6.086z");
}

</style>
