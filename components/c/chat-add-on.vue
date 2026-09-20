<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlep1698v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-add-on" /></template>
<style>
.dlep1698v {
  fill: currentColor;
  d: path("M7 9h8V7H7zm0 4h5v-2H7zm10 7v-3h-3v-2h3v-3h2v3h3v2h-3v3zM3 20V5q0-.825.588-1.412T5 3h12q.825 0 1.413.588T19 5v5.075q-.25-.05-.5-.062T18 10q-2.525 0-4.262 1.75T12 16q0 .25.013.5t.062.5H6z");
}

</style>
