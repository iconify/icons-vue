<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bezgdob2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:close-fullscreen-outline-sharp" /></template>
<style>
.bezgdob2x {
  fill: currentColor;
  d: path("M3.4 22L2 20.6L8.6 14H4v-2h8v8h-2v-4.6zM12 12V4h2v4.6L20.6 2L22 3.4L15.4 10H20v2z");
}

</style>
