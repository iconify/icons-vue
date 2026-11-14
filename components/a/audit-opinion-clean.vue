<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii93phnlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:audit-opinion-clean" /></template>
<style>
.ii93phnlw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.75Q3.25 2.75 3.25 6v8q0 3.122 3 3.245V20q0 .136.048.264q.048.127.138.23q.098.112.232.178q.133.066.282.076t.29-.038q.142-.047.254-.146l3.788-3.314H17.5q3.25 0 3.25-3.25V6q0-3.25-3.25-3.25zm4.5 8.439l3.97-3.969q.052-.053.113-.094t.13-.069t.141-.043T15.5 7t.146.014q.073.015.141.043t.13.069t.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-4.5 4.5q-.105.106-.243.163T11 13t-.287-.057t-.243-.163l-2.5-2.5q-.106-.105-.163-.243T7.75 9.75t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T8.5 9t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
