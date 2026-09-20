<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z529ausyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:coffee-maker-outline-sharp" /></template>
<style>
.z529ausyp {
  fill: currentColor;
  d: path("M5 21V3h14v1h-2.5v1.923h-8V4H6v16h4.512q-.893-.54-1.452-1.395q-.56-.855-.56-2.067v-4h8v4q0 1.212-.56 2.067q-.56.854-1.451 1.395H19v1zm7.5-1.461q1.25 0 2.125-.876t.875-2.125v-3h-6v3q0 1.25.875 2.125t2.125.875m.54-9.768q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.54.23t-.23.54t.23.54t.54.229t.54-.23m-.54 3.768");
}

</style>
