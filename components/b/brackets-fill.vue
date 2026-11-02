<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzox6rq7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brackets-fill" /></template>
<style>
.zzox6rq7q {
  fill: currentColor;
  d: path("M5 8v8h2a1 1 0 0 1 0 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h2a1 1 0 0 1 0 2Zm14-2a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-2a1 1 0 0 1 0-2h2V8h-2a1 1 0 0 1 0-2Z");
}

</style>
