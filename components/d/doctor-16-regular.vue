<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z7u0pktfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:doctor-16-regular" /></template>
<style>
.z7u0pktfl {
  fill: currentColor;
  d: path("M6.5 2.766a.5.5 0 0 0-.5.5v2.25a.5.5 0 0 1-.5.5h-2a.5.5 0 0 0-.5.5v2.985a.5.5 0 0 0 .5.5h2a.5.5 0 0 1 .5.5v2a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 1 .5-.5h2a.5.5 0 0 0 .5-.5v-3a.5.5 0 0 0-.5-.5h-2a.5.5 0 0 1-.5-.5V3.266a.5.5 0 0 0-.5-.5zm-1.5.5a1.5 1.5 0 0 1 1.5-1.5h3a1.5 1.5 0 0 1 1.5 1.5V5h1.5A1.5 1.5 0 0 1 14 6.5v3a1.5 1.5 0 0 1-1.5 1.5H11v1.5A1.5 1.5 0 0 1 9.5 14h-3A1.5 1.5 0 0 1 5 12.5V11H3.5A1.5 1.5 0 0 1 2 9.5V6.517a1.5 1.5 0 0 1 1.5-1.5H5z");
}

</style>
