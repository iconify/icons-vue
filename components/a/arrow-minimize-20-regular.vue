<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p77at4hxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-minimize-20-regular" /></template>
<style>
.p77at4hxs {
  fill: currentColor;
  d: path("M8.5 11a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-1 0v-3.793l-5.146 5.147a.5.5 0 0 1-.708-.707L7.293 12H3.5a.5.5 0 0 1 0-1zm8.647-8.854a.5.5 0 1 1 .707.708L12.707 8H16.5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5v-5a.5.5 0 0 1 1 0v3.793z");
}

</style>
