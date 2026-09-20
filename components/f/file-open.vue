<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g69i3f18s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-open" /></template>
<style>
.g69i3f18s {
  fill: currentColor;
  d: path("M21.95 22.375L19 19.425v2.225h-2V16h5.65v2H20.4l2.95 2.95zM13 9h5l-5-5zM6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h8l6 6v6h-5v8z");
}

</style>
