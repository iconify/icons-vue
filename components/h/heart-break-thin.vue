<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kf19m_bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:heart-break-thin" /></template>
<style>
.kf19m_bml {
  fill: currentColor;
  d: path("M178 44a57.6 57.6 0 0 0-41 17l-9 9l-9-9a58 58 0 0 0-99 41c0 28.59 18 58.47 53.4 88.79a334 334 0 0 0 52.7 36.73a4 4 0 0 0 3.8 0a334 334 0 0 0 52.7-36.73C218 160.47 236 130.59 236 102a58.07 58.07 0 0 0-58-58m-50 175.42c-14-8-100-59.35-100-117.42a50 50 0 0 1 85.36-35.36l9 9l-13.19 13.16a4 4 0 0 0 0 5.66l27.36 27.36l-19.36 19.35a4 4 0 0 0 5.66 5.66L145 124.64a4 4 0 0 0 0-5.65l-27.34-27.36l13.16-13.16l11.8-11.81A50 50 0 0 1 228 102c0 58-86 109.46-100 117.42");
}

</style>
