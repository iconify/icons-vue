<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l98l80czv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-marker-outline-sharp" /></template>
<style>
.l98l80czv {
  fill: currentColor;
  d: path("m6.8 21.4l-.95-.95L3.6 22.7l-2.25-2.35l2.2-2.2l-.95-1L17.175 2.575l4.25 4.25zm4.3-9.9l-5.7 5.65l1.45 1.45l5.65-5.7z");
}

</style>
