<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsghrtc6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-highlighter-move" /></template>
<style>
.gsghrtc6s {
  fill: currentColor;
  d: path("M13.775 4H7V2h8.775zm-4 4H4V6h7.775zm-4 4H1v-2h6.775zm4.825-2l5.4 5.4l-5 5q-.6.6-1.4.6t-1.4-.6l-.05-.05l-.65.65h-5l3.15-3.15l-.05-.05q-.6-.6-.6-1.4t.6-1.4zm1.425-1.425L17 3.6q.6-.6 1.4-.6t1.4.6l2.6 2.6q.6.6.6 1.4T22.4 9l-4.975 4.975z");
}

</style>
