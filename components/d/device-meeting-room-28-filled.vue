<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="w0zi1eccn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-28-filled" /></template>
<style>
.w0zi1eccn {
  fill: currentColor;
  d: path("M4.972 5.58A3.5 3.5 0 0 1 8.349 3h11.302a3.5 3.5 0 0 1 3.377 2.58l2.829 10.368C26.55 18.492 24.635 21 21.997 21H6.003c-2.638 0-4.554-2.508-3.86-5.052zM7.748 22.5a.75.75 0 1 0 0 1.5h12.503a.75.75 0 1 0 0-1.5z");
}

</style>
