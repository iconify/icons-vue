<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k8zvseboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-arrow-left-48-filled" /></template>
<style>
.k8zvseboh {
  fill: currentColor;
  d: path("M13 24c6.075 0 11 4.925 11 11s-4.925 11-11 11S2 41.075 2 35s4.925-11 11-11m11-8.75A3.75 3.75 0 0 0 27.75 19H40v22a3 3 0 0 1-3 3H22.376A12.95 12.95 0 0 0 26 35c0-7.18-5.82-13-13-13c-1.772 0-3.46.354-5 .996V7a3 3 0 0 1 3-3h13zM11.707 29.293a1 1 0 0 0-1.414 0l-5 5a1 1 0 0 0 0 1.414l5 5a1 1 0 1 0 1.414-1.414L8.414 36H20a1 1 0 1 0 0-2H8.414l3.293-3.293a1 1 0 0 0 0-1.414M39.462 16.5H27.75c-.69 0-1.25-.56-1.25-1.25V4.464z");
}

</style>
