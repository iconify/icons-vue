<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xhp3rhb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:energa" /></template>
<style>
.xhp3rhb2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.427 41.466l11.379-18.157c3.365-5.67 1.872-13.406-2.784-18.319a1.59 1.59 0 0 0-2.367.082C19.226 9.181 8.902 22.078 8.902 28.402C8.902 36.741 15.662 43.5 24 43.5s15.098-6.76 15.098-15.098c0-5.124-3.585-8.995-5.667-10.811c-.737-.643-1.874-.453-2.385.381l-4.317 7.055m-2.982 4.726l7.373 11.955");
}

</style>
