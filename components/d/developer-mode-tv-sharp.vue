<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0kuoacrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:developer-mode-tv-sharp" /></template>
<style>
.x0kuoacrp {
  fill: currentColor;
  d: path("M8 21v-2H2V3h20v16h-6v2zM4.8 11l2.6-2.6L6 7l-4 4l4 4l1.4-1.4zm14.4 0l-2.6 2.6L18 15l4-4l-4-4l-1.4 1.4z");
}

</style>
