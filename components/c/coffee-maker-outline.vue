<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok1mgl9ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:coffee-maker-outline" /></template>
<style>
.ok1mgl9ic {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3H19v1h-2.5v1.154q0 .327-.221.548t-.548.221H9.269q-.327 0-.548-.221T8.5 5.154V4H6.615q-.269 0-.442.173T6 4.616v14.769q0 .269.173.442t.442.173h3.896q-.892-.54-1.452-1.395T8.5 16.538v-4h8v4q0 1.212-.56 2.067q-.56.854-1.451 1.395H19v1zm5.884-1.462q1.25 0 2.125-.875t.875-2.125v-3h-6v3q0 1.25.875 2.125t2.125.875m.54-9.768q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.54.23t-.23.54t.23.54t.54.229t.54-.23m-.54 3.768");
}

</style>
