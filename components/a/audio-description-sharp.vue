<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgv49klyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:audio-description-sharp" /></template>
<style>
.vgv49klyy {
  fill: currentColor;
  d: path("M1 16V9l1-1h4l1 1v7H5v-2H3v2zm2-4h2v-2H3zm6 4V8h5l1 1v6l-1 1zm2-2h2v-4h-2zm6.85.8l-1.4-1.425q.275-.275.413-.625T17 12q0-.425-.137-.763t-.413-.612l1.4-1.45q.55.55.85 1.275T19 12t-.3 1.538t-.85 1.262m2.825 2.825l-1.45-1.375q.825-.825 1.3-1.912T21 12q0-1.275-.475-2.35t-1.3-1.9l1.45-1.4q1.1 1.1 1.712 2.55T23 12t-.612 3.088t-1.713 2.537");
}

</style>
