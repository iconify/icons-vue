<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz2-6ojnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bandage-fill" /></template>
<style>
.kz2-6ojnt {
  fill: currentColor;
  d: path("M5 19a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3Zm14-2a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1h-1v10ZM5 7a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h1V7Zm5.01 2H10a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m4 0H14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M10 13a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4.01 0H14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
