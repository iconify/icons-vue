<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p-fod0byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:badge-20-filled" /></template>
<style>
.p-fod0byo {
  fill: currentColor;
  d: path("M16 6a2 2 0 1 0 0-4a2 2 0 0 0 0 4m0 1c.35 0 .687-.06 1-.17V15a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h8.17A3 3 0 0 0 16 7");
}

</style>
