<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ifvy22bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-chat-empty-20-filled" /></template>
<style>
.ifvy22bba {
  fill: currentColor;
  d: path("M11.5 2a1.5 1.5 0 0 1 1.415 1H14.5A1.5 1.5 0 0 1 16 4.5v2.524A6.5 6.5 0 0 0 6 12.5c0 .98.222 1.909.611 2.744l-.548 1.825c-.093.311-.079.636.026.931H5.5A1.5 1.5 0 0 1 4 16.5v-12A1.5 1.5 0 0 1 5.5 3h1.585A1.5 1.5 0 0 1 8.5 2zm-3 1a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm4 4a5.5 5.5 0 1 1-2.652 10.315l-2.204.663a.5.5 0 0 1-.623-.622l.662-2.206A5.5 5.5 0 0 1 12.5 7");
}

</style>
