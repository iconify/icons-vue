<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="dc8ak2bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-28-filled" /></template>
<style>
.dc8ak2bqj {
  fill: currentColor;
  d: path("M14 21.25A2.75 2.75 0 0 1 11.25 24h-6.5A2.75 2.75 0 0 1 2 21.25l.004-10.75H14zM23.251 4a2.75 2.75 0 0 1 2.75 2.75v16.5a.75.75 0 0 1-1.5 0V9H2.004V6.75A2.75 2.75 0 0 1 4.754 4zM6.25 14a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5z");
}

</style>
