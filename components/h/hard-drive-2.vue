<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu48ffbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hard-drive-2" /></template>
<style>
.pu48ffbat {
  fill: currentColor;
  d: path("M14 19q.425 0 .713-.288T15 18t-.288-.712T14 17t-.712.288T13 18t.288.713T14 19m3 0q.425 0 .713-.288T18 18t-.288-.712T17 17t-.712.288T16 18t.288.713T17 19M3 13V4q0-.825.588-1.412T5 2h14q.825 0 1.413.588T21 4v9zm2 9q-.825 0-1.412-.587T3 20v-5h18v5q0 .825-.587 1.413T19 22z");
}

</style>
