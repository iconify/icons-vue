<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s24nbdcug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bird-scarer" /></template>
<style>
.s24nbdcug {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 21.5v-9.757q.872.507 2.25.507q3.75 0 3.75-3.75q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 7.75h-2.757q.507-.872.507-2.25q0-3.75-3.75-3.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.757Q10.378 4.75 9 4.75q-3.75 0-3.75 3.75q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T6 9.25h2.757q-.507.872-.507 2.25q0 3.354 3 3.708V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
