<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icxi9gm4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:conversation-close" /></template>
<style>
.icxi9gm4d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2.75H5q-1.346 0-2.298.952T1.75 6v8q0 3.122 3 3.245V20q0 .136.048.264q.048.127.138.23q.098.112.232.178q.133.066.282.076t.29-.038q.142-.047.254-.146l3.788-3.314H19q3.25 0 3.25-3.25V6q0-1.346-.952-2.298T19 2.75m-8 9.439l4.47-4.469q.052-.053.113-.094t.13-.069t.141-.043T16 7.5t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-5 5q-.105.106-.243.163T11 14t-.287-.057t-.243-.163l-3-3q-.106-.105-.163-.243t-.057-.287t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T8 9.5t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
