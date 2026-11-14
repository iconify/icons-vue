<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc5ltaczc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:audio-guide" /></template>
<style>
.bc5ltaczc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 11.75q-.26 0-.497.022q.078-2.649 1.974-4.545Q9.204 5.25 12 5.25t4.773 1.977q1.901 1.901 1.974 4.56q-.241-.037-.497-.037q-3 0-3 3v2.5q0 1.243.879 2.121q.878.879 2.121.879t2.121-.879q.879-.878.879-2.121v-2.5q0-1.243-.879-2.121q-.059-.06-.121-.116V12q0-3.417-2.416-5.834T12 3.75T6.166 6.166Q3.75 8.583 3.75 12v.286q-1 .732-1 2.464v2.5q0 1.243.879 2.121q.878.879 2.121.879t2.121-.879q.879-.878.879-2.121v-2.5q0-3-3-3");
}

</style>
