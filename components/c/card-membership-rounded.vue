<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgq274zpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:card-membership-rounded" /></template>
<style>
.zgq274zpx {
  fill: currentColor;
  d: path("M4 2h16q.825 0 1.413.588T22 4v11q0 .825-.587 1.413T20 17h-4v3.375q0 .575-.475.863t-.975.037l-2.1-1.05q-.2-.125-.45-.125t-.45.125l-2.1 1.05q-.5.25-.975-.037T8 20.375V17H4q-.825 0-1.412-.587T2 15V4q0-.825.588-1.412T4 2m0 11h16v-3H4z");
}

</style>
