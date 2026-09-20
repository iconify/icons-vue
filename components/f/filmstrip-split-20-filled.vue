<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cnuvrotsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filmstrip-split-20-filled" /></template>
<style>
.cnuvrotsp {
  fill: currentColor;
  d: path("M10.5 2.5a.5.5 0 0 0-1 0v15a.5.5 0 0 0 1 0zM2 7a3 3 0 0 1 3-3h3.5v12H5a3 3 0 0 1-3-3zm2.5-1a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5M4 13.5a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-1 0zM4.5 9a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5m7 7V4H15a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3zM15 7.5a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-1 0zm.5 4.5a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5M15 9.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-1 0");
}

</style>
