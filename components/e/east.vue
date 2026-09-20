<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmkmlebje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:east" /></template>
<style>
.tmkmlebje {
  fill: currentColor;
  d: path("m15 19l-1.425-1.4l4.6-4.6H2v-2h16.175L13.6 6.4L15 5l7 7z");
}

</style>
