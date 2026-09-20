<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns0y-k2xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-off-24-filled" /></template>
<style>
.ns0y-k2xh {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-2.201-2.2A9.96 9.96 0 0 1 12 22C6.477 22 2 17.523 2 12a9.96 9.96 0 0 1 2.419-6.52l-2.2-2.2a.75.75 0 0 1 0-1.06M12 2c5.523 0 10 4.477 10 10a9.95 9.95 0 0 1-1.52 5.298L6.7 3.52A9.95 9.95 0 0 1 12 2");
}

</style>
