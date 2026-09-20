<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aywadfx7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-shift-16-filled" /></template>
<style>
.aywadfx7a {
  fill: currentColor;
  d: path("M9.184 1.571a1.51 1.51 0 0 0-2.367 0L2.218 7.373c-.52.656-.05 1.621.789 1.621h1.978V13c0 .553.45 1.001 1.005 1.001h4.02c.556 0 1.005-.448 1.005-1.001V8.994h1.978c.84 0 1.31-.964.789-1.62z");
}

</style>
