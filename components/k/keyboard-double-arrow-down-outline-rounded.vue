<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k96wk90pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-double-arrow-down-outline-rounded" /></template>
<style>
.k96wk90pn {
  fill: currentColor;
  d: path("m12 16.175l3.9-3.875q.275-.275.688-.288t.712.288q.275.275.275.7t-.275.7l-4.6 4.6q-.15.15-.325.213t-.375.062t-.375-.062t-.325-.213l-4.6-4.6q-.275-.275-.288-.687T6.7 12.3q.275-.275.7-.275t.7.275zm0-6L15.9 6.3q.275-.275.688-.287t.712.287q.275.275.275.7t-.275.7l-4.6 4.6q-.15.15-.325.213t-.375.062t-.375-.062t-.325-.213L6.7 7.7q-.275-.275-.288-.687T6.7 6.3q.275-.275.7-.275t.7.275z");
}

</style>
