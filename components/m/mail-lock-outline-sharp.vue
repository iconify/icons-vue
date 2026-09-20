<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pblrwkblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mail-lock-outline-sharp" /></template>
<style>
.pblrwkblr {
  fill: currentColor;
  d: path("M2 20V4h20v5.975h-2V8l-8 5l-8-5v10h12v2zm10-9l8-5H4zm-8 7V6zm14 2v-5h1v-1q0-.825.588-1.412T21 12t1.413.588T23 14v1h1v5zm2-5h2v-1q0-.425-.288-.712T21 13t-.712.288T20 14z");
}

</style>
