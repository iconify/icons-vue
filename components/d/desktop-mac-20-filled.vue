<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wdxxthb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-mac-20-filled" /></template>
<style>
.wdxxthb3e {
  fill: currentColor;
  d: path("M4 2a2 2 0 0 0-2 2v9a2 2 0 0 0 2 2h4v1a1 1 0 0 1-1 1h-.5a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1H13a1 1 0 0 1-1-1v-1h4a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zM3 13v-1h14v1a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m5.732 4A2 2 0 0 0 9 16v-1h2v1c0 .364.097.706.268 1z");
}

</style>
