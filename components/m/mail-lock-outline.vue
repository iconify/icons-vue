<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r66n_8bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mail-lock-outline" /></template>
<style>
.r66n_8bke {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v3.975h-2V8l-8 5l-8-5v10h12v2zm8-9l8-5H4zm-8 7V6zm15 2q-.425 0-.712-.288T18 19v-3q0-.425.288-.712T19 15v-1q0-.825.588-1.412T21 12t1.413.588T23 14v1q.425 0 .713.288T24 16v3q0 .425-.288.713T23 20zm1-5h2v-1q0-.425-.288-.712T21 13t-.712.288T20 14z");
}

</style>
