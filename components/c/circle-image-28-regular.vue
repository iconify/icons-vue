<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="d6l0-cc3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-image-28-regular" /></template>
<style>
.d6l0-cc3d {
  fill: currentColor;
  d: path("M21.75 11A3.25 3.25 0 0 1 25 14.25v7.5A3.25 3.25 0 0 1 21.75 25h-7.5A3.25 3.25 0 0 1 11 21.75v-7.5A3.25 3.25 0 0 1 14.25 11zm-3.043 8.768a1 1 0 0 0-1.414 0l-3.63 3.63q.275.1.587.102h7.5q.31-.002.588-.102zM14.25 12.5a1.75 1.75 0 0 0-1.75 1.75v7.5q.002.31.102.588l3.63-3.631a2.5 2.5 0 0 1 3.536 0l3.63 3.63q.1-.275.102-.587v-7.5a1.75 1.75 0 0 0-1.75-1.75zM11 2a8 8 0 0 1 8 8h-1.5a6.5 6.5 0 1 0-7.5 6.423v1.513A8 8 0 0 1 11 2m9.5 12a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
