<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j1jjhp9kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-dismiss-48-filled" /></template>
<style>
.j1jjhp9kf {
  fill: currentColor;
  d: path("M13 24c6.075 0 11 4.925 11 11s-4.925 11-11 11S2 41.075 2 35s4.925-11 11-11m11-8.25A4.25 4.25 0 0 0 28.25 20H40v19.75A4.25 4.25 0 0 1 35.75 44H22.376A12.95 12.95 0 0 0 26 35c0-7.18-5.82-13-13-13c-1.772 0-3.46.354-5 .996V8.25A4.25 4.25 0 0 1 12.25 4H24zm-5.293 13.543a1 1 0 0 0-1.414 0L13 33.586l-4.293-4.293a1 1 0 1 0-1.414 1.414L11.586 35l-4.293 4.293a1 1 0 1 0 1.414 1.414L13 36.414l4.293 4.293a1 1 0 1 0 1.414-1.414L14.414 35l4.293-4.293a1 1 0 0 0 0-1.414M26.5 4.374c.466.21.895.503 1.263.871l10.992 10.992c.368.368.662.797.871 1.263H28.25a1.75 1.75 0 0 1-1.75-1.75z");
}

</style>
