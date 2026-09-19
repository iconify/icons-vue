<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aihrixdpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-done-outline" /></template>
<style>
.aihrixdpu {
  fill: currentColor;
  d: path("m19.77 5.03l1.4 1.4L8.43 19.17l-5.6-5.6l1.4-1.4l4.2 4.2zm0-2.83L8.43 13.54l-4.2-4.2L0 13.57L8.43 22L24 6.43z");
}

</style>
