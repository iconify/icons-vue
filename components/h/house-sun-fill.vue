<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe3969bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-sun-fill" /></template>
<style>
.oe3969bnv {
  fill: currentColor;
  d: path("M3 19v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l6 5.25A3 3 0 0 1 21 10.908V19a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3m8-10a1 1 0 0 0 2 0v-.5a1 1 0 0 0-2 0Zm-2.889 1.525l.353.354c.391.39 1.024.39 1.415 0c.39-.391.39-1.024 0-1.415l-.354-.353a.999.999 0 1 0-1.414 1.414m6.364-1.414l-.354.353a1 1 0 0 0 0 1.415c.391.39 1.024.39 1.415 0l.353-.354a.999.999 0 1 0-1.414-1.414m-4.317 3.11a2 2 0 1 0 3.684 1.558a2 2 0 0 0-3.684-1.558M8 14a1 1 0 0 0 0-2h-.5a1 1 0 0 0 0 2Zm8-2a1 1 0 0 0 0 2h.5a1 1 0 0 0 0-2Zm-6.475 4.889l.354-.353c.39-.391.39-1.024 0-1.415a1 1 0 0 0-1.415 0l-.353.354a.999.999 0 1 0 1.414 1.414m6.364-1.414l-.353-.354a1 1 0 0 0-1.415 0a1 1 0 0 0 0 1.415l.354.353a.999.999 0 1 0 1.414-1.414M13 17a1 1 0 0 0-2 0v.5a1 1 0 0 0 2 0Z");
}

</style>
