<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sjccut7cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-fit-in-16-filled" /></template>
<style>
.sjccut7cm {
  fill: currentColor;
  d: path("M3.72 6.28a.75.75 0 0 1 1.06-1.06l2 2a.75.75 0 0 1 0 1.06l-2 2a.75.75 0 1 1-1.06-1.06l.72-.72H1.75a.75.75 0 0 1 0-1.5h2.69zm8.56 0a.75.75 0 0 0-1.06-1.06l-2 2a.75.75 0 0 0 0 1.06l2 2a.75.75 0 1 0 1.06-1.06l-.72-.72h2.69a.75.75 0 0 0 0-1.5h-2.69z");
}

</style>
