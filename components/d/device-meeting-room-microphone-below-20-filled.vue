<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qlh-jxbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-microphone-below-20-filled" /></template>
<style>
.qlh-jxbtw {
  fill: currentColor;
  d: path("M17 15c0 .534-.284.987-.675 1.343c-.39.355-.928.652-1.55.891C13.53 17.714 11.84 18 10 18s-3.529-.286-4.775-.766c-.622-.239-1.16-.536-1.55-.891C3.284 15.987 3 15.534 3 15v-1.025c.412.37.923.69 1.485.953C5.923 15.598 7.873 16 10 16s4.078-.402 5.515-1.072A6 6 0 0 0 17 13.975zm-1.908-5.021c1.228.573 1.824 1.263 1.9 1.885q.006.067.008.136c0 .657-.59 1.406-1.908 2.021c-1.277.597-3.077.979-5.092.979s-3.815-.382-5.092-.979C3.59 13.407 3 12.657 3 12q.001-.069.008-.136c.075-.623.672-1.312 1.9-1.885C6.186 9.382 7.99 9 10 9s3.814.382 5.092.979m-.144-6.029a.5.5 0 0 1 .707.707a8 8 0 0 1-11.313 0a.5.5 0 1 1 .707-.707a7 7 0 0 0 9.9 0m-1.765-1.768a.5.5 0 0 1 .707.707a5.5 5.5 0 0 1-7.779 0a.5.5 0 1 1 .707-.707a4.5 4.5 0 0 0 6.365 0");
}

</style>
