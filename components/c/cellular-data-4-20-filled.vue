<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qn_g1fvid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cellular-data-4-20-filled" /></template>
<style>
.qn_g1fvid {
  fill: currentColor;
  d: path("M4.75 12a.75.75 0 0 1 .742.64l.008.11v2.5a.75.75 0 0 1-1.492.11L4 15.25v-2.5a.75.75 0 0 1 .75-.75m3-2a.75.75 0 0 1 .742.64l.008.11v4.5a.75.75 0 0 1-1.492.11L7 15.25v-4.5a.75.75 0 0 1 .75-.75");
}

</style>
