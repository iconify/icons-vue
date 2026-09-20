<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oo33-kbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-tower-20-filled" /></template>
<style>
.oo33-kbpn {
  fill: currentColor;
  d: path("M4 2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h2.085A1.5 1.5 0 0 1 7.5 16H7a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h3a2 2 0 0 0-2-2zm3 3a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h2v2H7.5a.5.5 0 0 0 0 1h8a.5.5 0 0 0 0-1H14v-2h2a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2zm6 12h-3v-2h3z");
}

</style>
