<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_knogbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:border-inner-outline-sharp" /></template>
<style>
.l_knogbbb {
  fill: currentColor;
  d: path("M3 21v-2h2v2zm0-4v-2h2v2zm0-8V7h2v2zm0-4V3h2v2zm4 16v-2h2v2zM7 5V3h2v2zm8 16v-2h2v2zm4 0v-2h2v2zm0-4v-2h2v2zm0-8V7h2v2zm0-4V3h2v2zm-4 0V3h2v2zm-4 16v-8H3v-2h8V3h2v8h8v2h-8v8z");
}

</style>
