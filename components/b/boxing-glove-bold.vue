<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wncojv7ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:boxing-glove-bold" /></template>
<style>
.wncojv7ie {
  fill: currentColor;
  d: path("M168 12h-48a60.08 60.08 0 0 0-59.87 56H56a36 36 0 0 0-36 36v29.19a20.13 20.13 0 0 0 4.38 12.5a12 12 0 0 0 .94 1L60 181v35a20 20 0 0 0 20 20h112a20 20 0 0 0 20-20v-38.32l15.23-53.3a20 20 0 0 0 .77-5.5V72a60.07 60.07 0 0 0-60-60m36 106.32l-15.54 54.38a12.3 12.3 0 0 0-.46 3.3v36H84v-36a12 12 0 0 0-3.56-8.53L44 131.45V104a12 12 0 0 1 12-12h4v12a12 12 0 0 0 24 0V72a36 36 0 0 1 36-36h48a36 36 0 0 1 36 36ZM166.66 162l-9 6l9 6a12 12 0 1 1-13.32 20L136 182.42L118.66 194a12 12 0 0 1-13.32-20l9-6l-9-6a12 12 0 0 1 13.32-20L136 153.58L153.34 142a12 12 0 1 1 13.32 20");
}

</style>
