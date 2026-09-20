<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clksywcok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:developer-mode-tv-outline-sharp" /></template>
<style>
.clksywcok {
  fill: currentColor;
  d: path("M3 7V4h18v3h-1V5H4v2zm6 13v-2H3v-3h1v2h16v-2h1v3h-6v2zm-4.584-9l2.6-2.6l-.708-.708L3 11l3.308 3.308l.708-.708zm15.169 0l-2.6 2.6l.707.708L21 11l-3.308-3.308l-.707.708z");
}

</style>
