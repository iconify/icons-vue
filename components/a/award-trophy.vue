<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blz8dn6gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:award-trophy" /></template>
<style>
.blz8dn6gj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.75h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.25H19q3.25 0 3.25 3.25q0 1.346-.952 2.298T19 11.25h-1.689q-.421.992-1.245 1.816q-1.413 1.412-3.316 1.64v2.044h1.5q1.036 0 1.768.732t.732 1.768v.5q0 1.036-.732 1.768t-1.768.732h-4.5q-1.036 0-1.768-.732T7.25 19.75v-.5q0-1.036.732-1.768t1.768-.732h1.5v-2.044q-1.903-.228-3.316-1.64q-.824-.824-1.245-1.816H5q-1.346 0-2.298-.952T1.75 8q0-3.25 3.25-3.25h1.25V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 2.75 7 2.75m-.75 3.5H5Q3.25 6.25 3.25 8q0 .725.513 1.237q.512.513 1.237.513h1.294Q6.25 9.384 6.25 9zM17.75 9q0 .384-.044.75H19q.725 0 1.237-.513q.513-.512.513-1.237q0-1.75-1.75-1.75h-1.25z");
}

</style>
