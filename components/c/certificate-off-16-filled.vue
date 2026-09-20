<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xlldo5c5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:certificate-off-16-filled" /></template>
<style>
.xlldo5c5p {
  fill: currentColor;
  d: path("M6 14.499a.5.5 0 0 1-.264.441a.5.5 0 0 1-.513-.024L4 14.1l-1.223.815A.498.498 0 0 1 2 14.5v-2.057A3.96 3.96 0 0 0 4 13a3.96 3.96 0 0 0 2-.556zM1.146 1.147a.5.5 0 0 1 .708 0l13 13a.5.5 0 1 1-.707.707L11.293 12H6.62a3.97 3.97 0 0 0 1.368-3.305L4.293 5H4c-1.202 0-2.267.54-3 1.38V4c0-.626.29-1.185.741-1.552l-.595-.594a.5.5 0 0 1 0-.707M4 6a3 3 0 1 1 0 6a3 3 0 0 1 0-6m9-4c1.103 0 2 .897 2 2v6a2 2 0 0 1-1.098 1.781L8.122 6H11.5a.5.5 0 0 0 0-1H7.121l-3-3z");
}

</style>
