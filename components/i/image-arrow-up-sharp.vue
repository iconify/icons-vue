<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oojswgb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:image-arrow-up-sharp" /></template>
<style>
.oojswgb7z {
  fill: currentColor;
  d: path("M3 21V3h10.8q-.4.675-.6 1.438T13 6q0 2.5 1.75 4.25T19 12q.525 0 1.025-.088T21 11.65V21zm3-4h12l-3.75-5l-3 4L9 13zm12-7V5.825L16.4 7.4L15 6l4-4l4 4l-1.4 1.4L20 5.825V10z");
}

</style>
