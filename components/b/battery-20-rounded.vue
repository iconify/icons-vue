<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afbdmcb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-20-rounded" /></template>
<style>
.afbdmcb-q {
  fill: currentColor;
  d: path("M8 22q-.425 0-.712-.288T7 21V5q0-.425.288-.712T8 4h2V3q0-.425.288-.712T11 2h2q.425 0 .713.288T14 3v1h2q.425 0 .713.288T17 5v16q0 .425-.288.713T16 22z");
}

</style>
