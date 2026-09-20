<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh3-ujp9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-previous-language" /></template>
<style>
.jh3-ujp9x {
  fill: currentColor;
  d: path("M4 22q-.825 0-1.412-.587T2 20V10q0-.825.588-1.412T4 8h16q.825 0 1.413.588T22 10v10q0 .825-.587 1.413T20 22zm4-3h8v-2H8zm-3-3h2v-2H5zm3 0h2v-2H8zm3 0h2v-2h-2zm3 0h2v-2h-2zm3 0h2v-2h-2zM5 13h2v-2H5zm3 0h2v-2H8zm3 0h2v-2h-2zm3 0h2v-2h-2zm3 0h2v-2h-2zM6 6V1h2v1.525Q8.8 1.8 9.825 1.4T12 1q2.2 0 3.875 1.413T17.9 6h-2.05q-.35-1.325-1.412-2.162T12 3q-.75 0-1.425.263T9.375 4H11v2z");
}

</style>
