<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj-x9pbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-pen-rounded" /></template>
<style>
.tj-x9pbmq {
  fill: currentColor;
  d: path("M15.275 12.475L11.525 8.7L14.3 5.95l-.725-.725L8.8 10q-.3.3-.7.3t-.7-.3t-.3-.712t.3-.713l4.75-4.75q.6-.6 1.413-.6t1.412.6l.725.725l1.25-1.25q.3-.3.713-.3t.712.3L20.7 5.625q.3.3.3.713t-.3.712zM4 21q-.425 0-.712-.288T3 20v-1.925q0-.4.15-.763t.425-.637l6.525-6.55l3.775 3.75l-6.55 6.55q-.275.275-.637.425t-.763.15z");
}

</style>
