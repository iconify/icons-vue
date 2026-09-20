<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xfg6_8b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chat-circle-slash-bold" /></template>
<style>
.xfg6_8b-n {
  fill: currentColor;
  d: path("M56.88 31.93a12 12 0 1 0-17.76 16.14l7.81 8.59a108 108 0 0 0-15.08 120.57L21 209.66A20 20 0 0 0 46.34 235l32.43-10.81a108.08 108.08 0 0 0 112.55-8.66l7.8 8.58a12 12 0 0 0 17.76-16.14ZM128 212a83.9 83.9 0 0 1-42-11.27a12 12 0 0 0-9.82-1l-29.79 9.93l9.93-29.79a12 12 0 0 0-1-9.82a84 84 0 0 1 7.94-95.49l111.84 123A83.83 83.83 0 0 1 128 212m108-84a107.2 107.2 0 0 1-8.65 42.4a12 12 0 0 1-22.07-9.4A84.07 84.07 0 0 0 102.51 48a12 12 0 0 1-7.27-22.87A108.08 108.08 0 0 1 236 128");
}

</style>
