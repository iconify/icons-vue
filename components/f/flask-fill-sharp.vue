<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqncge4hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flask-fill-sharp" /></template>
<style>
.iqncge4hb {
  fill: currentColor;
  d: path("M8 2h8a1 1 0 0 1 0 2h-1v4.764l5.894 11.789c.07.139.106.292.106.447v.004A1 1 0 0 1 20 22H4a1 1 0 0 1-.894-1.447L9 8.764V4H8a1 1 0 0 1 0-2m3 7a1 1 0 0 1-.106.447L8.618 14h6.764l-2.276-4.553A1 1 0 0 1 13 9V4h-2Z");
}

</style>
