<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vbz9zjmpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-status-bar-20-regular" /></template>
<style>
.vbz9zjmpp {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2zm2-1a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h5.5V5zm12 10a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1h-5.5v10zm-4-9a.5.5 0 0 0 0 1h3.5a.5.5 0 0 0 0-1z");
}

</style>
