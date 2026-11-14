<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wff8aqbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:clothes-hanger" /></template>
<style>
.wff8aqbdu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4.5q-3 0-3 3q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146Q10.5 6 12 6t1.5 1.5T12 9q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v1.756q-.689.197-1.378.757l-2.345 1.905q-1.413 1.149-.804 2.865q.61 1.717 2.431 1.717h5.692q1.821 0 2.431-1.717q.609-1.716-.804-2.865l-2.345-1.905q-.689-.56-1.378-.757v-1.06Q15 10.098 15 7.5q0-3-3-3");
}

</style>
