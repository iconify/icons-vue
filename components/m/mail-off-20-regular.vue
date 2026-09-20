<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y0t1g_b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-off-20-regular" /></template>
<style>
.y0t1g_b1x {
  fill: currentColor;
  d: path("M2.854 2.146a.5.5 0 1 0-.708.708l1.355 1.354A2.5 2.5 0 0 0 2 6.5v8A2.5 2.5 0 0 0 4.5 17h11q.362-.001.695-.098l.951.952a.5.5 0 0 0 .708-.708zM15.293 16H4.5A1.5 1.5 0 0 1 3 14.5V7.963l6.746 3.968l.082.038a.5.5 0 0 0 .426-.038l.61-.36zm-5.159-5.159L10 10.92L3 6.802V6.5a1.5 1.5 0 0 1 1.305-1.487zM17 6.801l-5.085 2.992l.73.73L17 7.962V14.5q0 .175-.039.34l.777.776A2.5 2.5 0 0 0 18 14.5v-8A2.5 2.5 0 0 0 15.5 4H6.121l1 1H15.5A1.5 1.5 0 0 1 17 6.5z");
}

</style>
