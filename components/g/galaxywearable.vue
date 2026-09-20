<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rpmwcwb2w"/><path class="ll0g54h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:galaxywearable" /></template>
<style>
.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.rpmwcwb2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.4 19.2L18 28.8l-2.4-9.6l-2.4 9.6l-2.4-9.6m24 5.6c0-1.3 1.1-2.4 2.4-2.4m-2.4.1v6.3m-9.2-1.2c-.4.7-1.2 1.2-2.1 1.2c-1.3 0-2.4-1.1-2.4-2.4v-1.6c0-1.3 1.1-2.4 2.4-2.4s2.4 1 2.4 2.3v.8h-4.8m11.6.9c0 1.3-1.1 2.4-2.4 2.4S28 27.7 28 26.4v-1.6c0-1.3 1.1-2.4 2.4-2.4s2.4 1.1 2.4 2.4m-.1 4v-6.3");
}

</style>
