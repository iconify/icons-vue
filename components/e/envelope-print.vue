<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1vokmn1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:envelope-print" /></template>
<style>
.v1vokmn1e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 16.75H5q-2.75 0-2.75-2.75v-4q0-2.75 2.75-2.75h1.25V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 2.25 7 2.25h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v4.25H19q2.75 0 2.75 2.75v4q0 2.75-2.75 2.75h-1.25v3q0 1.036-.732 1.768t-1.768.732h-6.5q-1.036 0-1.768-.732T6.25 19.75zm10-9.5v-3.5h-8.5v3.5zM5 8.75q-1.25 0-1.25 1.25v4q0 1.25 1.25 1.25h1.25v-1.5q0-.489.096-.883q.084.149.224.247l5 3.5q.094.067.205.101q.11.035.225.035t.225-.035q.111-.034.205-.101l5-3.5q.14-.098.224-.247q.096.393.096.883v1.5H19q1.25 0 1.25-1.25v-4q0-1.25-1.25-1.25zm2.014 3q.229.004.416.136L12 15.085l4.57-3.199q.187-.132.416-.136q-.618-.5-1.736-.5h-6.5q-1.118 0-1.736.5");
}

</style>
