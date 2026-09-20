<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak4xehkue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:audio-capture-outline" /></template>
<style>
.ak4xehkue {
  fill: currentColor;
  d: path("M2 22V12h2v5.125L5.15 16H8v2H6zm14-4v-2h4v-4h2v4q0 .825-.587 1.413T20 18zm-5-3V5h2v10zm-4-2V7h2v6zm8-1V8h2v4zM2 8V4q0-.825.588-1.412T4 2h4v2H4v4zm18 0V4h-4V2h4q.825 0 1.413.588T22 4v4z");
}

</style>
