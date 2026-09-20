<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yeci3uj-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gpp-maybe" /></template>
<style>
.yeci3uj-d {
  fill: currentColor;
  d: path("M12.713 15.713Q13 15.425 13 15t-.288-.712T12 14t-.712.288T11 15t.288.713T12 16t.713-.288M11 12h2V7h-2zm1 10q-3.475-.875-5.738-3.988T4 11.1V5l8-3l8 3v6.1q0 3.8-2.262 6.913T12 22");
}

</style>
