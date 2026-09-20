<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mc4d9ubfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-chat-empty-32-filled" /></template>
<style>
.mc4d9ubfl {
  fill: currentColor;
  d: path("M19 2c1.306 0 2.417.835 2.83 2h1.67A3.5 3.5 0 0 1 27 7.5v4.885a10.45 10.45 0 0 0-6-1.885c-5.799 0-10.5 4.701-10.5 10.5c0 1.57.348 3.064.969 4.405l-.864 2.877A2.5 2.5 0 0 0 10.71 30H8.5A3.5 3.5 0 0 1 5 26.5v-19A3.5 3.5 0 0 1 8.5 4h1.67A3 3 0 0 1 13 2zm-6 2a1 1 0 1 0 0 2h6a1 1 0 1 0 0-2zm8 8a9 9 0 1 1-4.269 16.924l-3.443 1.034a1.001 1.001 0 0 1-1.246-1.245l1.033-3.445A9 9 0 0 1 21 12");
}

</style>
