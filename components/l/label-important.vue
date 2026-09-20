<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8nwtgget"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:label-important" /></template>
<style>
.p8nwtgget {
  fill: currentColor;
  d: path("m3 19l5.5-7L3 4.98h11.673q.379 0 .718.156q.338.155.555.453L21 12l-5.034 6.392q-.218.299-.556.453t-.718.155z");
}

</style>
