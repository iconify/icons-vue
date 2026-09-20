<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q7_zyu6ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:center-vertical-20-filled" /></template>
<style>
.q7_zyu6ph {
  fill: currentColor;
  d: path("M2.5 3a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1zM2 16.5a.5.5 0 0 1 .5-.5h15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1-.5-.5M6 7a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V9a2 2 0 0 0-2-2z");
}

</style>
