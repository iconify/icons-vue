<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l24xy0bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lockout-breaker" /></template>
<style>
.l24xy0bms {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 1.75h9.75q3.375 0 3.375 3.375v5.879Q18.127 11 18 11q-4 0-4 4v.007q-1.5.871-1.5 3.243v1H5.125q-3.375 0-3.375-3.375V5.125q0-3.375 3.375-3.375m3.125 3.5h-.5q-2.5 0-2.5 2.5v5.5q0 1.036.732 1.768t1.768.732h.5q1.036 0 1.768-.732t.732-1.768v-2H14q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14 9.75h-3.25v-2q0-2.5-2.5-2.5m13.268 11.232q-.35-.349-.768-.532V15q0-2.75-2.75-2.75T15.25 15v.877q-1.5.437-1.5 2.373v1.5q0 2.5 2.5 2.5h3.5q1.036 0 1.768-.732t.732-1.768v-1.5q0-1.036-.732-1.768M19.25 15v.75h-2.5V15q0-1.25 1.25-1.25T19.25 15m-4 3.25q0-1 1-1h3.5q1 0 1 1v1.5q0 .414-.293.707t-.707.293h-3.5q-.414 0-.707-.293t-.293-.707zm1.25.25h.807q-.342.305-.807.486z");
}

</style>
