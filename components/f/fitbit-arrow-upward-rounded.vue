<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6zzn46tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fitbit-arrow-upward-rounded" /></template>
<style>
.r6zzn46tc {
  fill: currentColor;
  d: path("M11 9.825L8.1 12.7q-.275.275-.688.288T6.7 12.7q-.275-.275-.275-.7t.275-.7l4.6-4.6q.3-.3.7-.3t.7.3l4.6 4.6q.275.275.288.688t-.288.712q-.275.275-.7.275t-.7-.275L13 9.825V17q0 .425-.288.713T12 18q-.425 0-.713-.288T11 17V9.825Z");
}

</style>
