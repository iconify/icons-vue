<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzpf218rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:journalism-award" /></template>
<style>
.pzpf218rz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.75h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.25h.75q3.25 0 3.25 3.25q0 1.346-.952 2.298t-2.298.952h-1.433q-.389.704-1.001 1.316q-1.413 1.412-3.316 1.64v3.044h2q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-5.5q-1.036 0-1.768-.732T6.75 19.75q0-2.5 2.5-2.5h2v-3.044q-1.903-.228-3.316-1.64q-.612-.612-1.001-1.316H5.5q-1.346 0-2.298-.952T2.25 8q0-3.25 3.25-3.25h.75V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 2.75 7 2.75m-.75 3.5H5.5Q3.75 6.25 3.75 8q0 .725.513 1.237q.512.513 1.237.513h.876Q6.25 9.151 6.25 8.5zm12.25 0h-.75V8.5q0 .651-.126 1.25h.876q.725 0 1.237-.513q.513-.512.513-1.237q0-1.75-1.75-1.75");
}

</style>
