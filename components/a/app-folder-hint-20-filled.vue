<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gv2jwo57n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:app-folder-hint-20-filled" /></template>
<style>
.gv2jwo57n {
  fill: currentColor;
  d: path("M2.5 14a.5.5 0 0 1 .5.5v.5a2 2 0 0 0 2 2h.5a.5.5 0 0 1 0 1H5a3 3 0 0 1-3-3v-.5a.5.5 0 0 1 .5-.5m9 3a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1zm6-3a.5.5 0 0 1 .5.5v.5a3 3 0 0 1-3 3h-.5a.5.5 0 0 1 0-1h.5a2 2 0 0 0 2-2v-.5a.5.5 0 0 1 .5-.5M8 11a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1zm6 0a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1zM2.5 8a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-1 0v-3a.5.5 0 0 1 .5-.5m15 0a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-1 0v-3a.5.5 0 0 1 .5-.5M8 5a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1zm6 0a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1zM5.5 2a.5.5 0 0 1 0 1H5a2 2 0 0 0-2 2v.5a.5.5 0 0 1-1 0V5a3 3 0 0 1 3-3zM15 2a3 3 0 0 1 3 3v.5a.5.5 0 0 1-1 0V5a2 2 0 0 0-2-2h-.5a.5.5 0 0 1 0-1zm-3.5 0a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1z");
}

</style>
