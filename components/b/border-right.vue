<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh1cw1bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:border-right" /></template>
<style>
.mh1cw1bkm {
  fill: currentColor;
  d: path("M7 21h2v-2H7zM3 5h2V3H3zm4 0h2V3H7zm0 8h2v-2H7zm-4 8h2v-2H3zm8 0h2v-2h-2zm-8-8h2v-2H3zm0 4h2v-2H3zm0-8h2V7H3zm8 8h2v-2h-2zm4-4h2v-2h-2zm4-10v18h2V3zm-4 18h2v-2h-2zm0-16h2V3h-2zm-4 8h2v-2h-2zm0-8h2V3h-2zm0 4h2V7h-2z");
}

</style>
