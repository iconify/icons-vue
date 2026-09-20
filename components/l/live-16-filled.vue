<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oa0_wlnmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:live-16-filled" /></template>
<style>
.oa0_wlnmy {
  fill: currentColor;
  d: path("M3.05 3.05a.75.75 0 0 1 1.06 1.06a5.5 5.5 0 0 0 0 7.778a.75.75 0 0 1-1.06 1.06a7 7 0 0 1 0-9.9m8.838 0a.75.75 0 0 1 1.06 0a7 7 0 0 1 0 9.9a.75.75 0 1 1-1.06-1.061a5.5 5.5 0 0 0 0-7.778a.75.75 0 0 1 0-1.061M5.174 5.172a.75.75 0 1 1 1.06 1.06a2.5 2.5 0 0 0 0 3.536a.75.75 0 0 1-1.06 1.06a4 4 0 0 1 0-5.656m4.596 0a.75.75 0 0 1 1.06 0a4 4 0 0 1 0 5.656a.75.75 0 1 1-1.06-1.06a2.5 2.5 0 0 0 0-3.535a.75.75 0 0 1 0-1.061M8 7a1 1 0 1 1 0 2a1 1 0 0 1 0-2");
}

</style>
