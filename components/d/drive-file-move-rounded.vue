<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo7i_wbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drive-file-move-rounded" /></template>
<style>
.lo7i_wbfu {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h5.175q.4 0 .763.15t.637.425L12 6h8q.825 0 1.413.588T22 8v10q0 .825-.587 1.413T20 20zm8.2-6l-.925.925q-.275.275-.275.7t.275.7t.7.275t.7-.275L15.3 13.7q.3-.3.3-.7t-.3-.7l-2.625-2.625q-.275-.275-.7-.275t-.7.275t-.275.7t.275.7L12.2 12H9q-.425 0-.712.288T8 13t.288.713T9 14z");
}

</style>
