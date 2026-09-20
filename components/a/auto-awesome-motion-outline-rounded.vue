<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm88vfjrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-awesome-motion-outline-rounded" /></template>
<style>
.nm88vfjrp {
  fill: currentColor;
  d: path("M12 22q-.825 0-1.412-.587T10 20v-8q0-.825.588-1.412T12 10h8q.825 0 1.413.588T22 12v8q0 .825-.587 1.413T20 22zm0-2h8v-8h-8zm-6-3V8q0-.825.588-1.412T8 6h9q.425 0 .713.288T18 7t-.288.713T17 8H8v9q0 .425-.288.713T7 18t-.712-.288T6 17m-4-4V4q0-.825.588-1.412T4 2h9q.425 0 .713.288T14 3t-.288.713T13 4H4v9q0 .425-.288.713T3 14t-.712-.288T2 13m10 7v-8z");
}

</style>
