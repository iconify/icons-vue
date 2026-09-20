<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a807-8xmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-paint" /></template>
<style>
.a807-8xmh {
  fill: currentColor;
  d: path("M11 22q-.825 0-1.412-.587T9 20v-4H6q-.825 0-1.412-.587T4 14V7q0-1.65 1.175-2.825T8 3h12v11q0 .825-.587 1.413T18 16h-3v4q0 .825-.587 1.413T13 22zM6 10h12V5h-1v4h-2V5h-1v2h-2V5H8q-.825 0-1.412.588T6 7z");
}

</style>
