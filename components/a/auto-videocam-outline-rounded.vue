<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8jdtv-ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-videocam-outline-rounded" /></template>
<style>
.h8jdtv-ko {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.413-.588T2 18V6q0-.825.588-1.413T4 4h12q.825 0 1.413.588T18 6v4.5l3.15-3.15q.25-.25.55-.125t.3.475v8.6q0 .35-.3.475t-.55-.125L18 13.5V18q0 .825-.588 1.413T16 20H4Zm0-2h12V6H4v12Zm0 0V6v12Zm4.75-4.75l.8 1.75q.125.3.45.3t.45-.3l.8-1.75l1.75-.8q.3-.125.3-.45t-.3-.45l-1.75-.8l-.8-1.75q-.125-.3-.45-.3t-.45.3l-.8 1.75l-1.75.8q-.3.125-.3.45t.3.45l1.75.8Z");
}

</style>
