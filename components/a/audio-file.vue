<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu4iy0b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:audio-file" /></template>
<style>
.eu4iy0b3d {
  fill: currentColor;
  d: path("M10.75 18.692q.816 0 1.379-.563q.563-.564.563-1.379v-3.98h2.731v-1.54h-3.5v4.087q-.236-.257-.53-.383q-.293-.126-.643-.126q-.815 0-1.379.563q-.563.564-.563 1.379t.563 1.379q.564.563 1.379.563M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3H14.5L19 7.5v11.885q0 .69-.462 1.153T17.384 21zM14 8h4l-4-4z");
}

</style>
