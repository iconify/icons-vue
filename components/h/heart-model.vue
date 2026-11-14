<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n89gi8bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-model" /></template>
<style>
.n89gi8bbm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.959 7.284q-.712-.403-1.709-.39V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q9.574 2.25 9.5 2.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T8.75 3v4.118q-1.303.374-2.28 1.352q-1.816 1.815-1.593 4.713q.23 2.984 2.593 5.347q2.375 2.376 4.793 3.182q.141.047.29.036q.149-.01.282-.077Q19.75 18.214 19.75 11.5q0-2.992-1.543-4.279q.058-.017.113-.043t.105-.06t.094-.076t.08-.091t.065-.102q.028-.054.047-.111q.02-.058.029-.117t.01-.121v-1q0-3-3-3t-3 3v1.274q-.413.212-.791.51m2.291-.983V5.5q0-1.5 1.5-1.5t1.5 1.5v1q0 .077.016.152Q16.315 6.25 15 6.25q-.385 0-.75.051");
}

</style>
