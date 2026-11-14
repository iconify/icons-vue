<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me9lui1il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:debug-print" /></template>
<style>
.me9lui1il {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 7.25h-1.25V3.5q0-1.75-1.75-1.75H8q-1.75 0-1.75 1.75v3.75H5q-3.25 0-3.25 3.25V15q0 3.25 3.25 3.25h1.25v1.5q0 1.036.732 1.768t1.768.732h6.5q1.036 0 1.768-.732t.732-1.768v-1.5H19q3.25 0 3.25-3.25v-4.5q0-1.346-.952-2.298T19 7.25M7.75 3.5q0-.25.25-.25h8q.25 0 .25.25v3.75h-8.5zM5 8.75h14q1.75 0 1.75 1.75V15q0 1.75-1.75 1.75h-1.25v-1q0-2.5-2.5-2.5h-6.5q-2.5 0-2.5 2.5v1H5q-1.75 0-1.75-1.75v-4.5q0-1.75 1.75-1.75m9.5 8.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.75 18t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
