<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf3yynqtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:business-messages-sharp" /></template>
<style>
.hf3yynqtc {
  fill: currentColor;
  d: path("M5 20V8.75L1 4h21v16zm8.5-2.5l1.4-1.4l-1.1-1.1H18v-2H9zM9 11h9l-4.5-4.5l-1.4 1.4L13.2 9H9z");
}

</style>
