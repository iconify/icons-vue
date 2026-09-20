<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uft-ojbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:code" /></template>
<style>
.uft-ojbmz {
  fill: currentColor;
  d: path("M8 17.308L2.692 12L8 6.692l.714.714l-4.6 4.6L8.708 16.6zm8 0l-.713-.714l4.6-4.6L15.292 7.4L16 6.692L21.308 12z");
}

</style>
