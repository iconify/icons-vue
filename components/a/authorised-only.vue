<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwrgygb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:authorised-only" /></template>
<style>
.rwrgygb0f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.141 3.391Q5.75 4.782 5.75 6.75t1.391 3.359T10.5 11.5t3.359-1.391T15.25 6.75t-1.391-3.359T10.5 2T7.141 3.391M2.25 21q0-3.498 2.376-5.874T10.5 12.75q2.654 0 4.662 1.368q-.438.568-.586 1.427q-1.724-1.295-4.076-1.295q-2.877 0-4.813 1.937Q3.75 18.123 3.75 21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T3 21.75t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 21m18.768-3.518q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
