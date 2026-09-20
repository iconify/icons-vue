<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n46a6-cvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ambient-screen-outline" /></template>
<style>
.n46a6-cvr {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.413-.588T2 18V6q0-.825.588-1.413T4 4h16q.825 0 1.413.588T22 6v6.025h-2V6H4v12h10.025v2H4Zm15.5 1l-1.1-2.4l-2.4-1.1l2.4-1.1l1.1-2.4l1.1 2.4l2.4 1.1l-2.4 1.1l-1.1 2.4ZM4 18V6v12v-.5v.5Zm8-2l1.25-2.75L16 12l-2.75-1.25L12 8l-1.25 2.75L8 12l2.75 1.25L12 16Z");
}

</style>
