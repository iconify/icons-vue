<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg5nh6mgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:alarm-add" /></template>
<style>
.yg5nh6mgv {
  fill: currentColor;
  d: path("M11.5 16.5h1v-3h3v-1h-3v-3h-1v3h-3v1h3zm-2.618 3.874q-1.455-.626-2.542-1.713t-1.714-2.542T4 13.001t.626-3.12T6.34 7.34t2.54-1.714T12 5t3.12.626t2.54 1.714t1.713 2.54T20 13t-.626 3.12t-1.714 2.542t-2.54 1.713T12 21t-3.12-.626M5.909 3.427l.707.707l-3.48 3.481l-.708-.707zm12.184 0l3.481 3.48l-.707.709l-3.481-3.481z");
}

</style>
