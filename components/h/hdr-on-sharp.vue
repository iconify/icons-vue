<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf1lp4r4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hdr-on-sharp" /></template>
<style>
.wf1lp4r4p {
  fill: currentColor;
  d: path("M16.308 14.692V9.308h3.788l.596.596v2.112l-.596.615h-.458l.9 2.061h-.923l-.9-2h-1.523v2zm.884-2.884h2.616v-1.616h-2.616zM3.308 14.692V9.308h.884v2h2.616v-2h.884v5.384h-.884v-2.5H4.192v2.5zm6.5 0V9.308h3.788l.596.596v4.173l-.596.615zm.884-.884h2.616v-3.616h-2.616z");
}

</style>
