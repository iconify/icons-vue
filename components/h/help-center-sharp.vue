<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5rbzubku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:help-center-sharp" /></template>
<style>
.n5rbzubku {
  fill: currentColor;
  d: path("M12.599 16.907q.228-.228.228-.56q0-.334-.228-.562q-.228-.227-.56-.227t-.561.227t-.228.561t.228.56t.56.229t.561-.228m-1.076-3.084h.966q.038-.67.247-1.065q.21-.397.802-.989q.721-.721 1.046-1.25q.324-.53.324-1.204q0-1.17-.804-1.887t-1.964-.717q-1.067 0-1.837.57q-.77.569-1.126 1.365l.92.381q.251-.598.718-.991q.468-.394 1.264-.394q.944 0 1.404.517q.46.516.46 1.174q0 .501-.276.919q-.275.417-.77.877q-.807.744-1.09 1.34t-.284 1.354M4 20V4h16v16z");
}

</style>
