<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="it8s52hud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filmstrip-arrow-up-20-regular" /></template>
<style>
.it8s52hud {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-.003 2a.5.5 0 0 0-.349.145l-2.001 2.002a.5.5 0 1 0 .707.707L14 13.707V16.5a.5.5 0 0 0 1 0v-2.793l1.146 1.146a.5.5 0 1 0 .707-.707l-2-2a.5.5 0 0 0-.35-.146zM15.5 4A2.5 2.5 0 0 1 18 6.5v3.757a5.5 5.5 0 0 0-1-.656V6.5A1.5 1.5 0 0 0 15.5 5h-11A1.5 1.5 0 0 0 3 6.5v7A1.5 1.5 0 0 0 4.5 15h4.523q.047.517.185 1H4.5A2.5 2.5 0 0 1 2 13.5v-7A2.5 2.5 0 0 1 4.5 4zm-11 8a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0v-1a.5.5 0 0 1 .5-.5m0-3a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0v-1a.5.5 0 0 1 .5-.5m0-3a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0v-1a.5.5 0 0 1 .5-.5m11 0a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0v-1a.5.5 0 0 1 .5-.5");
}

</style>
