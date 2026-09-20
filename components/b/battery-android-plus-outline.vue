<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6vyv6b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-plus-outline" /></template>
<style>
.l6vyv6b4r {
  fill: currentColor;
  d: path("M3 16V8zm1 2q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h12v2H4q-.425 0-.712.288T3 9v6q0 .425.288.713T4 16h12v2zm14-2v-3h-3v-2h3V8h2v3h3v2h-3v3z");
}

</style>
