<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh9crca4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hand-package-outline" /></template>
<style>
.rh9crca4c {
  fill: currentColor;
  d: path("M15 4H9v7h6zm5 0h-3v7h3zm-5.625 9H8v6h5.55q.525 0 1.013-.175t.887-.525l4.15-3.425q-.2-.2-.45-.3t-.525-.15q-.425-.075-.825.025t-.75.375L14.35 17H10v-2h3.65l1.1-.9q.125-.075.188-.2t.062-.275q0-.25-.187-.437T14.375 13M6 13H4v7h2zm1 0V4q0-.825.588-1.412T9 2h11q.825 0 1.413.588T22 4v7q0 .825-.587 1.413T20 13zm-1 9H4q-.825 0-1.412-.587T2 20v-7q0-.825.588-1.412T4 11h10.375q2.125 0 4.1.725t3.175 2.45l.675 1.025l-5.575 4.65q-.675.575-1.5.863t-1.7.287H7.725q-.275.45-.725.725T6 22");
}

</style>
