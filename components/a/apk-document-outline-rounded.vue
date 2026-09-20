<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7l59kbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:apk-document-outline-rounded" /></template>
<style>
.d7l59kbyu {
  fill: currentColor;
  d: path("M7 19h10q-.1-1.225-.75-2.25t-1.7-1.625l.95-1.7q.05-.1.025-.225t-.15-.175q-.1-.05-.213-.025t-.162.125l-.975 1.75q-.5-.2-1-.312T12 14.45t-1.025.113t-1 .312L9 13.125Q8.95 13 8.838 13t-.238.05l-.1.375l.95 1.7q-1.05.6-1.7 1.625T7 19m2.4-1.65q-.15-.15-.15-.35t.15-.35t.35-.15t.35.15t.15.35t-.15.35t-.35.15t-.35-.15m4.5 0q-.15-.15-.15-.35t.15-.35t.35-.15t.35.15t.15.35t-.15.35t-.35.15t-.35-.15M6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h7.175q.4 0 .763.15t.637.425l4.85 4.85q.275.275.425.638t.15.762V20q0 .825-.587 1.413T18 22zm7-14V4H6v16h12V9h-4q-.425 0-.712-.288T13 8M6 4v5zv16z");
}

</style>
