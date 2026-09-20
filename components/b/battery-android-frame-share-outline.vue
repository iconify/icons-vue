<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt0ogybzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-frame-share-outline" /></template>
<style>
.tt0ogybzh {
  fill: currentColor;
  d: path("M4 18q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h14.175l-2 2H4q-.425 0-.712.288T3 9v6q0 .425.288.713T4 16h7v2zm9-2v-3q0-.825.588-1.412T15 11h4.175L17.6 9.4L19 8l4 4l-4 4l-1.425-1.425l1.6-1.575H15v3zm-2-1H4V9h11.175q-1.725 0-2.95 1.113T11 13z");
}

</style>
