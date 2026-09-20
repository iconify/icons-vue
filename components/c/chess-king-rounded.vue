<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr_1dacjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chess-king-rounded" /></template>
<style>
.vr_1dacjz {
  fill: currentColor;
  d: path("M6.692 10.596q-.58-.511-.934-1.242t-.354-1.565q0-1.587 1.091-2.688Q7.587 4 9.173 4q.64 0 1.237.228q.596.228 1.09.632V2.5q0-.213.143-.357T12 2t.357.143t.143.357v2.34q.494-.378 1.09-.61q.597-.23 1.218-.23q1.586 0 2.687 1.101t1.101 2.688q0 .853-.354 1.575q-.354.72-.934 1.232zM5.616 21q-.672 0-1.144-.472T4 19.385v-1.539q0-.69.463-1.153t1.153-.462H6.98l.385-3.02H4.5q-.213 0-.357-.143T4 12.712t.143-.357t.357-.143h15q.214 0 .357.143t.143.357t-.143.356t-.357.144h-2.884L17 16.23h1.385q.69 0 1.152.462T20 17.846v1.538q0 .672-.472 1.144T18.385 21z");
}

</style>
