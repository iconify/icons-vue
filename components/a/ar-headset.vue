<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebneovbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ar-headset" /></template>
<style>
.ebneovbit {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 9.75h-1.801q-.31-2.194-2.492-3.544Q15.057 4.875 12 4.875T6.793 6.206Q4.611 7.556 4.301 9.75H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146v4q0 3.75 3.75 3.75h4q.149 0 .287-.057t.243-.163L12 16.061l1.97 1.969q.105.106.243.163t.287.057h4q3.75 0 3.75-3.75v-4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014M12 6.375q-5.653 0-6.193 3.375h12.386Q17.653 6.375 12 6.375");
}

</style>
