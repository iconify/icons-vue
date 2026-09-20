<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ig6lefbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:highlight-accent-16-filled" /></template>
<style>
.ig6lefbee {
  fill: currentColor;
  d: path("M13.5 2v3a.5.5 0 0 1-.5.5H3a.5.5 0 0 1-.5-.5V2zm-8 6.5h5v1.867a2 2 0 0 1-.971 1.716L5.5 14.5z");
}

</style>
