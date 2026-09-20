<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-vssgy2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-bottom-thick-24-filled" /></template>
<style>
.p-vssgy2u {
  fill: currentColor;
  d: path("M14 4a1 1 0 0 1-1 1h-2a1 1 0 1 1 0-2h2a1 1 0 0 1 1 1m-9 7a1 1 0 1 0-2 0v2a1 1 0 1 0 2 0zm14 0a1 1 0 1 1 2 0v2a1 1 0 1 1-2 0zM6 3a1 1 0 0 1 0 2a1 1 0 0 0-1 1a1 1 0 0 1-2 0a3 3 0 0 1 3-3m11 1a1 1 0 0 1 1-1a3 3 0 0 1 3 3a1 1 0 1 1-2 0a1 1 0 0 0-1-1a1 1 0 0 1-1-1M5.5 17.25v.5c0 .414.336.75.75.75h11.5a.75.75 0 0 0 .75-.75v-.5a1.25 1.25 0 1 1 2.5 0V18h-.01a3.25 3.25 0 0 1-3.24 3H6.25a3.25 3.25 0 0 1-3.24-3H3v-.75a1.25 1.25 0 1 1 2.5 0");
}

</style>
