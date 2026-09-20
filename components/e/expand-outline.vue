<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoiuz9awn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:expand-outline" /></template>
<style>
.zoiuz9awn {
  fill: currentColor;
  d: path("M4 22v-2h16v2zm8-3l-4-4l1.4-1.4l1.6 1.55v-6.3L9.4 10.4L8 9l4-4l4 4l-1.4 1.4L13 8.85v6.3l1.6-1.55L16 15zM4 4V2h16v2z");
}

</style>
