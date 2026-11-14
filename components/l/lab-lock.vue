<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb4j2mb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lab-lock" /></template>
<style>
.xb4j2mb0f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.52 9.924l9-7.5q.05-.042.107-.074q.056-.033.118-.055t.125-.034q.065-.011.13-.011t.13.011t.125.034q.062.022.118.055q.057.032.107.074l9 7.5q.128.107.199.258t.071.318v5.954q-.125-.113-.255-.213Q21.368 13 18 13q-3.238 0-3.48 2.995Q13 16.863 13 19.25v.5q0 1.118.569 2H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 21V10.5q0-.167.071-.318t.199-.258m18.498 7.558q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
