<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1-ae7uew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:delete-forever-outline-sharp" /></template>
<style>
.i1-ae7uew {
  fill: currentColor;
  d: path("m9.4 16.5l2.6-2.6l2.6 2.6l1.4-1.4l-2.6-2.6L16 9.9l-1.4-1.4l-2.6 2.6l-2.6-2.6L8 9.9l2.6 2.6L8 15.1zM5 21V6H4V4h5V3h6v1h5v2h-1v15zm2-2h10V6H7zM7 6v13z");
}

</style>
