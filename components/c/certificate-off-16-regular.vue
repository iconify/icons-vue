<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lq7rcib-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:certificate-off-16-regular" /></template>
<style>
.lq7rcib-n {
  fill: currentColor;
  d: path("M6 14.499a.5.5 0 0 1-.264.441a.5.5 0 0 1-.513-.024L4 14.1l-1.223.815A.498.498 0 0 1 2 14.5v-2.057A3.96 3.96 0 0 0 4 13a3.96 3.96 0 0 0 2-.556zM1.146 1.147a.5.5 0 0 1 .708 0l13 13a.5.5 0 1 1-.707.707L11.293 12H7v-.354q.263-.3.465-.646h2.828L2.455 3.162A1 1 0 0 0 2 4v1.535a4 4 0 0 0-1 .82V4c0-.627.29-1.185.741-1.552l-.595-.594a.5.5 0 0 1 0-.707M4 6a3 3 0 1 1 0 6a3 3 0 0 1 0-6m9-4a2 2 0 0 1 2 2v6c0 .78-.447 1.452-1.097 1.782l-.789-.789A1 1 0 0 0 14 10V4a1 1 0 0 0-1-1H5.121l-1-1zm-1.5 3a.5.5 0 0 1 0 1H8.121l-1-1z");
}

</style>
