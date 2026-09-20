<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hf6af9v-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-microphone-above-20-filled" /></template>
<style>
.hf6af9v-t {
  fill: currentColor;
  d: path("M6.111 17.111a5.5 5.5 0 0 1 7.779 0a.5.5 0 0 1-.707.707a4.5 4.5 0 0 0-6.365 0a.5.5 0 0 1-.707-.707m-1.77-1.768a8 8 0 0 1 11.314 0a.5.5 0 0 1-.707.707a7 7 0 0 0-9.9 0a.5.5 0 1 1-.706-.707M10 5c2.015 0 3.815.382 5.092.979C16.41 6.593 17 7.343 17 8q-.002.069-.009.136c-.075.623-.671 1.312-1.9 1.886C13.815 10.618 12.01 11 10 11s-3.814-.382-5.092-.979c-1.228-.573-1.825-1.262-1.9-1.885A2 2 0 0 1 3 8c0-.657.59-1.407 1.908-2.021C6.185 5.382 7.985 5 10 5m0-3c1.84 0 3.529.286 4.775.766c.622.239 1.16.536 1.55.891c.391.356.675.809.675 1.343v1.025a6 6 0 0 0-1.485-.953C14.078 4.402 12.127 4 10 4s-4.077.402-5.515 1.072A6 6 0 0 0 3 6.025V5c0-.534.284-.987.675-1.343c.39-.355.928-.652 1.55-.891C6.47 2.286 8.16 2 10 2");
}

</style>
