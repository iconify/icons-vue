<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1859gb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-delete-outline" /></template>
<style>
.g1859gb-g {
  fill: currentColor;
  d: path("M14.5 17h2q.625 0 1.063-.437T18 15.5v-4h1V10h-2.5V9h-2v1H12v1.5h1v4q0 .625.438 1.063T14.5 17m0-5.5h2v4h-2zM4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h6l2 2h8q.825 0 1.413.588T22 8v10q0 .825-.587 1.413T20 20zm0-2h16V8h-8.825l-2-2H4zm0 0V6z");
}

</style>
