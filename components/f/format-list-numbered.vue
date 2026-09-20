<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvjac6mvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-list-numbered" /></template>
<style>
.kvjac6mvw {
  fill: currentColor;
  d: path("M3 22v-1.5h2.5v-.75H4v-1.5h1.5v-.75H3V16h3q.425 0 .713.288T7 17v1q0 .425-.288.713T6 19q.425 0 .713.288T7 20v1q0 .425-.288.713T6 22zm0-7v-2.75q0-.425.288-.712T4 11.25h1.5v-.75H3V9h3q.425 0 .713.288T7 10v1.75q0 .425-.288.713T6 12.75H4.5v.75H7V15zm1.5-7V3.5H3V2h3v6zM9 19v-2h12v2zm0-6v-2h12v2zm0-6V5h12v2z");
}

</style>
