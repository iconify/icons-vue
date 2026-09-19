<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpmywwn1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:border-top" /></template>
<style>
.gpmywwn1p {
  fill: currentColor;
  d: path("M7 21h2v-2H7zm0-8h2v-2H7zm4 0h2v-2h-2zm0 8h2v-2h-2zm-8-4h2v-2H3zm0 4h2v-2H3zm0-8h2v-2H3zm0-4h2V7H3zm8 8h2v-2h-2zm8-8h2V7h-2zm0 4h2v-2h-2zM3 3v2h18V3zm16 14h2v-2h-2zm-4 4h2v-2h-2zM11 9h2V7h-2zm8 12h2v-2h-2zm-4-8h2v-2h-2z");
}

</style>
