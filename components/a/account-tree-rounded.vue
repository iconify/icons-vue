<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbi4bkc-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:account-tree-rounded" /></template>
<style>
.jbi4bkc-f {
  fill: currentColor;
  d: path("M15 19v-1h-2q-.825 0-1.412-.587T11 16V8H9v1q0 .825-.587 1.413T7 11H4q-.825 0-1.412-.587T2 9V5q0-.825.588-1.412T4 3h3q.825 0 1.413.588T9 5v1h6V5q0-.825.588-1.412T17 3h3q.825 0 1.413.588T22 5v4q0 .825-.587 1.413T20 11h-3q-.825 0-1.412-.587T15 9V8h-2v8h2v-1q0-.825.588-1.412T17 13h3q.825 0 1.413.588T22 15v4q0 .825-.587 1.413T20 21h-3q-.825 0-1.412-.587T15 19");
}

</style>
