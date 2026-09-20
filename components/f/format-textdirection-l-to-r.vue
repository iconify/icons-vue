<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl4gbgbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-textdirection-l-to-r" /></template>
<style>
.vl4gbgbwj {
  fill: currentColor;
  d: path("M9 15v-5q-1.65 0-2.825-1.175T5 6t1.175-2.825T9 2h8v2h-2v11h-2V4h-2v11zm8 7l-1.4-1.4l1.6-1.6H3v-2h14.2l-1.6-1.6L17 14l4 4z");
}

</style>
