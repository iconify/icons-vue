<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5z4mrbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-image-back-outline-sharp" /></template>
<style>
.t5z4mrbpi {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4v-2h4v-2H3v-2h4V9H3V7h18v2h-4v2h4v2h-4v2h4v2zm6-2h6v-2H9zm0-4h6V9H9zM3 5V3h18v2zm9 6");
}

</style>
