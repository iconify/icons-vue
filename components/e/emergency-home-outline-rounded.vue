<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4i0_6w4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:emergency-home-outline-rounded" /></template>
<style>
.m4i0_6w4x {
  fill: currentColor;
  d: path("M11.238 21.875q-.363-.15-.663-.425L2.55 13.425q-.275-.3-.425-.663T1.975 12t.15-.775t.425-.65l8.025-8.025q.3-.3.663-.438T12 1.975t.775.138t.65.437l8.025 8.025q.3.275.438.65t.137.775t-.137.763t-.438.662l-8.025 8.025q-.275.275-.65.425t-.775.15t-.763-.15m.763-1.85L20.025 12L12 3.975L3.975 12zm.713-7.312Q13 12.425 13 12V8q0-.425-.288-.712T12 7t-.712.288T11 8v4q0 .425.288.713T12 13t.713-.288m0 3Q13 15.426 13 15t-.288-.712T12 14t-.712.288T11 15t.288.713T12 16t.713-.288M12 12");
}

</style>
