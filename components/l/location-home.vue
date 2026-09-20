<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7ar0gbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:location-home" /></template>
<style>
.z7ar0gbzu {
  fill: currentColor;
  d: path("M14.125 14.125Q15 13.25 15 12t-.875-2.125T12 9t-2.125.875T9 12t.875 2.125T12 15t2.125-.875M6 19h12v-.275q0-.35-.15-.65t-.45-.475q-1.225-.775-2.587-1.187T12 16t-2.812.413T6.6 17.6q-.3.175-.45.475t-.15.65zm-2 2V9l8-6l8 6v12z");
}

</style>
