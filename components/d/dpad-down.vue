<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyu2pcc2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dpad-down" /></template>
<style>
.gyu2pcc2f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.25 1.75h-4.5q-2.5 0-2.5 2.5v2q0 1-1 1h-2q-1.036 0-1.768.732T1.75 9.75v4.5q0 2.5 2.5 2.5h2q1 0 1 1v2q0 1.036.732 1.768t1.768.732h4.5q1.036 0 1.768-.732t.732-1.768v-2q0-1 1-1h2q1.036 0 1.768-.732t.732-1.768v-4.5q0-1.036-.732-1.768T19.75 7.25h-2q-1 0-1-1v-2q0-2.5-2.5-2.5M12 18.189l-1.97-1.969q-.052-.053-.113-.094t-.13-.069t-.141-.043T9.5 16t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113l2.5 2.5q.052.053.113.094t.13.069t.141.043T12 20t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l2.5-2.5q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14.5 16t-.146.014q-.073.015-.141.043t-.13.069t-.113.094z");
}

</style>
