<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0acnj7-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-frame-alert" /></template>
<style>
.u0acnj7-i {
  fill: currentColor;
  d: path("M20.288 16.213Q20 15.925 20 15.5t.288-.712T21 14.5t.713.288t.287.712t-.288.713T21 16.5t-.712-.288M20 13V7h2v6zM4 18q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h14v2H4q-.425 0-.712.288T3 9v6q0 .425.288.713T4 16h14q0 .575.213 1.088t.562.912zm0-3V9h14v6z");
}

</style>
