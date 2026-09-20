<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qhx29xhhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-16-filled" /></template>
<style>
.qhx29xhhq {
  fill: currentColor;
  d: path("M2.739 3.459A2 2 0 0 1 4.665 2h6.67c.896 0 1.683.596 1.926 1.459l1.66 5.898A2.08 2.08 0 0 1 12.917 12H3.083a2.08 2.08 0 0 1-2.004-2.643zM4.497 13a.5.5 0 1 0 0 1h7.005a.5.5 0 1 0 0-1z");
}

</style>
