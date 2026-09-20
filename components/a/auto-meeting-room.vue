<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrmq_rpyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-meeting-room" /></template>
<style>
.hrmq_rpyu {
  fill: currentColor;
  d: path("M1 21v-2h2V3h10v1h4v8h-2V6h-2v15H1Zm8-8q.425 0 .713-.288T10 12q0-.425-.288-.713T9 11q-.425 0-.713.288T8 12q0 .425.288.713T9 13Zm10 9l1.25-2.75L23 18l-2.75-1.25L19 14l-1.25 2.75L15 18l2.75 1.25L19 22Z");
}

</style>
