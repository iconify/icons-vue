<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgf7_rb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-no-meeting-room" /></template>
<style>
.qgf7_rb0c {
  fill: currentColor;
  d: path("M11 11h-1v2h2v-1l9.73 9.73L20.46 23L14 16.54V21H3v-2h2V7.54l-4-4l1.27-1.27zm3 .49L5.51 3H14v1h5v12.49l-2-2V6h-3z");
}

</style>
