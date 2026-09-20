<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zb67by9sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-chat-empty-32-regular" /></template>
<style>
.zb67by9sv {
  fill: currentColor;
  d: path("M19 2c1.306 0 2.417.835 2.83 2h1.67A3.5 3.5 0 0 1 27 7.5v4.885a10.5 10.5 0 0 0-2-1.095V7.5A1.5 1.5 0 0 0 23.5 6h-1.67A3 3 0 0 1 19 8h-6a3 3 0 0 1-2.83-2H8.5A1.5 1.5 0 0 0 7 7.5v19A1.5 1.5 0 0 0 8.5 28h2.19l-.085.282A2.5 2.5 0 0 0 10.71 30H8.5A3.5 3.5 0 0 1 5 26.5v-19A3.5 3.5 0 0 1 8.5 4h1.67A3 3 0 0 1 13 2zm-6 2a1 1 0 1 0 0 2h6a1 1 0 1 0 0-2zm8 8a9 9 0 1 1-4.269 16.924l-3.443 1.034a1.001 1.001 0 0 1-1.246-1.245l1.033-3.445A9 9 0 0 1 21 12m0 2a7 7 0 0 0-5.99 10.627a1 1 0 0 1 .104.806l-.623 2.074l2.074-.622a1 1 0 0 1 .808.103A7 7 0 1 0 21 14");
}

</style>
