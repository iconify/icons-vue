<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0pk4xq1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-line-24-filled" /></template>
<style>
.s0pk4xq1d {
  fill: currentColor;
  d: path("M21.972 12.75H2.027C2.411 17.922 6.73 22 12 22s9.588-4.078 9.972-9.25m0-1.5H2.027C2.411 6.077 6.73 2 12 2s9.588 4.077 9.972 9.25");
}

</style>
