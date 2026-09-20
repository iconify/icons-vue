<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajbdsobrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-repair" /></template>
<style>
.ajbdsobrs {
  fill: currentColor;
  d: path("M11.5 20.77v-3h-7v-1h15v1h-7v3zm-2.345-8.961q.23-.23.23-.54t-.23-.54t-.54-.229t-.539.23t-.23.54q0 .309.23.539t.54.23t.539-.23m6.769 0q.23-.23.23-.54t-.23-.54t-.54-.229t-.539.23t-.23.54t.23.539t.54.23t.539-.23M6 9.523l1.496-4.3q.067-.215.24-.334q.172-.12.387-.12h7.754q.215 0 .388.12q.172.119.239.334L18 9.523v5.793q0 .196-.129.325q-.129.128-.325.128h-.092q-.196 0-.325-.128q-.129-.13-.129-.325v-1.547H7v1.546q0 .197-.129.326q-.129.128-.325.128h-.092q-.196 0-.325-.129T6 15.316zm1.304-.754h9.392l-1.046-3h-7.3z");
}

</style>
