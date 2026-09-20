<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hj6dddb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-32-regular" /></template>
<style>
.hj6dddb0a {
  fill: currentColor;
  d: path("M9.47 4a4.25 4.25 0 0 0-4.096 3.113L2.154 18.7c-.738 2.665 1.265 5.3 4.03 5.3h19.634c2.765 0 4.768-2.635 4.028-5.299l-3.22-11.588A4.25 4.25 0 0 0 22.53 4zM7.302 7.648A2.25 2.25 0 0 1 9.47 6h13.06a2.25 2.25 0 0 1 2.168 1.648l3.22 11.589a2.18 2.18 0 0 1-2.1 2.763H6.182a2.18 2.18 0 0 1-2.1-2.764zM7.999 26a1 1 0 1 0 0 2h16.002a1 1 0 1 0 0-2z");
}

</style>
