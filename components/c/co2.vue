<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z39tvnb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:co2" /></template>
<style>
.z39tvnb8z {
  fill: currentColor;
  d: path("M11.077 14.692q-.31 0-.54-.23t-.23-.539v-3.846q0-.31.23-.54t.54-.23h2.846q.31 0 .54.23t.23.54v3.846q0 .31-.23.54t-.54.23zm.115-.884h2.616v-3.616h-2.616zm-7.115.884q-.31 0-.54-.23t-.23-.539v-3.846q0-.31.23-.54t.54-.23h2.846q.31 0 .54.23t.23.54v.615h-.885v-.5H4.192v3.616h2.616v-.5h.884v.615q0 .31-.23.54t-.539.23zm13.23 3v-2.307q0-.31.23-.54t.54-.23h2.23v-1.423h-3v-.884h3.116q.31 0 .54.23t.23.539v1.539q0 .309-.23.539t-.54.23h-2.23v1.423h3v.884z");
}

</style>
