<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_mxupb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:g-mobiledata-outline-rounded" /></template>
<style>
.g_mxupb-a {
  fill: currentColor;
  d: path("M9 17q-.825 0-1.412-.587T7 15V9q0-.825.588-1.412T9 7h6q.425 0 .713.288T16 8t-.288.713T15 9H9v6h5v-2h-1q-.425 0-.712-.288T12 12t.288-.712T13 11h2q.425 0 .713.288T16 12v3q0 .825-.587 1.413T14 17z");
}

</style>
