<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqet4ab9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:label-important-outline" /></template>
<style>
.hqet4ab9o {
  fill: currentColor;
  d: path("m3 19l5.5-7L3 4.98h11.673q.379 0 .717.156q.339.155.556.453L21 12l-5.034 6.392q-.218.299-.556.453q-.34.155-.718.155zm2-1h9.712q.154 0 .269-.058q.115-.057.211-.173L19.75 12l-4.558-5.788q-.096-.116-.211-.173q-.115-.058-.27-.058H5L9.75 12zm7.385-6.02");
}

</style>
