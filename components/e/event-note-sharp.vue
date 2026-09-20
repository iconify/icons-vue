<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etmu36brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:event-note-sharp" /></template>
<style>
.etmu36brr {
  fill: currentColor;
  d: path("M7 14v-2h10v2zm0 4v-2h7v2zm-4 4V4h3V2h2v2h8V2h2v2h3v18zm2-2h14V10H5z");
}

</style>
