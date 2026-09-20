<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jhl31stdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-space-fit-vertical-20-filled" /></template>
<style>
.jhl31stdw {
  fill: currentColor;
  d: path("M6 1a2 2 0 0 0-2 2v4.5a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V3a2 2 0 0 0-2-2zm0 9.5a2 2 0 0 0-2 2V17a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-4.5a2 2 0 0 0-2-2z");
}

</style>
