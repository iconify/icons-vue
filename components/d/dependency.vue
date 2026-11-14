<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctks9db9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dependency" /></template>
<style>
.ctks9db9g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.375 2.25h-4.25q-1.398 0-2.386.989q-.989.988-.989 2.386v.75q0 3.375 3.375 3.375H6.5V18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2.939l-.719.72q-.053.052-.094.113t-.069.13t-.043.141T9.25 20t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163l.873-.872q.565 2.092 3.222 2.092h4.25q3.375 0 3.375-3.375v-.75q0-3.375-3.375-3.375h-4.25q-2.657 0-3.222 2.092l-.873-.872q-.052-.053-.113-.094t-.13-.069t-.141-.043T10 15.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T9.25 16t.014.146q.015.073.043.141t.069.13q.041.061.094.113l.719.72H8v-7.5h1.375q1.398 0 2.386-.989q.989-.988.989-2.386v-.75q0-1.398-.989-2.386q-.988-.989-2.386-.989");
}

</style>
