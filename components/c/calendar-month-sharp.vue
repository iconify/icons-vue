<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7c5m0b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:calendar-month-sharp" /></template>
<style>
.k7c5m0b4e {
  fill: currentColor;
  d: path("M11 14v-2h2v2zm-4 0v-2h2v2zm8 0v-2h2v2zm-4 4v-2h2v2zm-4 0v-2h2v2zm8 0v-2h2v2zM3 22V4h3V2h2v2h8V2h2v2h3v18zm2-2h14V10H5z");
}

</style>
