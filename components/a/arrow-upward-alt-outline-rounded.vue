<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzsnx9bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-upward-alt-outline-rounded" /></template>
<style>
.zzsnx9bop {
  fill: currentColor;
  d: path("m11 8.8l-2.9 2.9q-.275.275-.7.275t-.7-.275t-.275-.7t.275-.7l4.6-4.6q.3-.3.7-.3t.7.3l4.6 4.6q.275.275.275.7t-.275.7t-.7.275t-.7-.275L13 8.8V17q0 .425-.288.713T12 18t-.712-.288T11 17z");
}

</style>
