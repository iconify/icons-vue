<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wpiwiseaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-32-filled" /></template>
<style>
.wpiwiseaq {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2-2h22a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2zm1 6h24v12.5a5.5 5.5 0 0 1-5.5 5.5h-13A5.5 5.5 0 0 1 4 23.5zm9 3a1 1 0 1 0 0 2h6a1 1 0 1 0 0-2z");
}

</style>
