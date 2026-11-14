<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uofmwvbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:garden-measuring-tape" /></template>
<style>
.uofmwvbac {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 3.75H14q3.75 0 3.75 3.75v7.25h3.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146V19q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-16q-3.75 0-3.75-3.75V7.5q0-1.553 1.098-2.652Q3.947 3.75 5.5 3.75m.5 8q0 3.75 3.75 3.75t3.75-3.75T9.75 8T6 11.75m11.75 6.5h3v-2h-3z");
}

</style>
