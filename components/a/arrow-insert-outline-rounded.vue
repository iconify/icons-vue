<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfth3xskz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-insert-outline-rounded" /></template>
<style>
.yfth3xskz {
  fill: currentColor;
  d: path("M8 8.4V16q0 .425-.288.713T7 17t-.712-.288T6 16V6q0-.425.288-.712T7 5h10q.425 0 .713.288T18 6t-.288.713T17 7H9.4l8.9 8.9q.275.275.275.7t-.275.7t-.7.275t-.7-.275z");
}

</style>
