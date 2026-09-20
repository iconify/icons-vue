<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov1e71hbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-improvement-and-tools-outline-sharp" /></template>
<style>
.ov1e71hbp {
  fill: currentColor;
  d: path("M6 2h12l-3 4.2V19l-3 3l-3-3V6.2zm5 8h2V5.6L14 4h-4l1 1.6zm2 2h-2v2h2zm0 6v-2h-2v2l1 1zm-1-2");
}

</style>
