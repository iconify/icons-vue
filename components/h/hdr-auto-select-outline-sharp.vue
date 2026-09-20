<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzioa3b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hdr-auto-select-outline-sharp" /></template>
<style>
.yzioa3b3e {
  fill: currentColor;
  d: path("m10.95 8.316l1-2.747h.062l1.038 2.747zm-2.488 3.227Q7 10.086 7 8.005T8.457 4.46T11.995 3t3.544 1.457T17 7.996t-1.457 3.542T12.005 13T8.46 11.543m.75-.812h.816l.65-1.685h2.646l.65 1.685h.893l-2.574-6.462h-.634zm11.597 10.961v-2h-2v-.884h2v-2h.884v2h2v.884h-2v2zm-7.5 0v-5.384h4.384v3.323H16.64l.9 2.061h-.924l-.9-2h-1.523v2zm.884-2.884h2.616v-1.616h-2.616zM.308 21.692v-5.384h.884v2h2.616v-2h.884v5.384h-.884v-2.5H1.192v2.5zm6.5 0v-5.384h3.942l.442.442v4.5l-.442.442zm.884-.884h2.616v-3.616H7.692z");
}

</style>
