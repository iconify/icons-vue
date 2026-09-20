<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdbgkzb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:6k-sharp" /></template>
<style>
.qdbgkzb1a {
  fill: currentColor;
  d: path("M12.885 14.692h.884v-2.365l2.289 2.365h1.211l-2.634-2.73l2.634-2.654h-1.173l-2.327 2.327V9.308h-.885zm-6 0h3.884v-3.076h-3v-1.424h3v-.884H6.885zm.884-.769v-1.538h2.116v1.538zM4 20V4h16v16z");
}

</style>
