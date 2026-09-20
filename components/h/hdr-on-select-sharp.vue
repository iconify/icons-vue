<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr5tt1_as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hdr-on-select-sharp" /></template>
<style>
.tr5tt1_as {
  fill: currentColor;
  d: path("M8.462 11.543Q7 10.086 7 8.005T8.457 4.46T11.995 3t3.544 1.457T17 7.996t-1.457 3.542T12.005 13T8.46 11.543m12.347 10.15v-2h-2v-.885h2v-2h.884v2h2v.884h-2v2zm-7.5 0v-5.385h4.384v3.323H16.64l.9 2.061h-.924l-.9-2h-1.523v2zm.884-2.885h2.616v-1.616h-2.616zM.308 21.692v-5.384h.884v2h2.616v-2h.884v5.384h-.884v-2.5H1.192v2.5zm6.5 0v-5.384h3.942l.442.442v4.5l-.442.442zm.884-.884h2.616v-3.616H7.692z");
}

</style>
