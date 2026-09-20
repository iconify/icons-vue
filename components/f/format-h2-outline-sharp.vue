<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu1sngblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-h2-outline-sharp" /></template>
<style>
.vu1sngblr {
  fill: currentColor;
  d: path("M3 17V7h2v4h4V7h2v10H9v-4H5v4zm10 0v-4q0-.825.588-1.412T15 11h4V9h-6V7h6q.825 0 1.413.588T21 9v2q0 .825-.587 1.413T19 13h-4v2h6v2z");
}

</style>
