<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0av9ifps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drive-folder-upload-rounded" /></template>
<style>
.t0av9ifps {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h5.175q.4 0 .763.15t.637.425L12 6h8q.825 0 1.413.588T22 8v10q0 .825-.587 1.413T20 20zm8.713-3.287Q13 16.425 13 16v-3.2l.9.9q.275.275.7.275t.7-.275t.275-.7t-.275-.7l-2.6-2.6q-.3-.3-.7-.3t-.7.3l-2.6 2.6q-.275.275-.275.7t.275.7t.7.275t.7-.275l.9-.9V16q0 .425.288.713T12 17t.713-.288");
}

</style>
