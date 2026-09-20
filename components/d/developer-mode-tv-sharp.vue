<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqbpfyb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:developer-mode-tv-sharp" /></template>
<style>
.xqbpfyb2y {
  fill: currentColor;
  d: path("M9 20v-2H3V4h18v14h-6v2zm-4.584-9l2.6-2.6l-.708-.708L3 11l3.308 3.308l.708-.708zm15.169 0l-2.6 2.6l.707.708L21 11l-3.308-3.308l-.707.708z");
}

</style>
