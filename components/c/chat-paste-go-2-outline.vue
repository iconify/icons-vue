<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc3g0lbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-paste-go-2-outline" /></template>
<style>
.pc3g0lbto {
  fill: currentColor;
  d: path("m18 21l-1.4-1.4l1.575-1.6H14v-2h4.175L16.6 14.4L18 13l4 4zM3 21V6q0-.825.588-1.412T5 4h12q.825 0 1.413.588T19 6v5.075q-.25-.05-.5-.062T18 11t-.5.013t-.5.062V6H5v10h7.075q-.05.25-.062.5T12 17t.013.5t.062.5H6zm2-5V6z");
}

</style>
