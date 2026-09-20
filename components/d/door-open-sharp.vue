<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wela2lb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:door-open-sharp" /></template>
<style>
.wela2lb1m {
  fill: currentColor;
  d: path("M3 21v-2h2V3h14v16h2v2zm12-2h2V5h-2zm-3.287-6.287Q12 12.425 12 12t-.288-.712T11 11t-.712.288T10 12t.288.713T11 13t.713-.288");
}

</style>
