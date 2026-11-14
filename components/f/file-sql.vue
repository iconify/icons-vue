<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amucctufq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:file-sql" /></template>
<style>
.amucctufq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75H7q-1.346 0-2.298.952T3.75 5v14q0 1.346.952 2.298T7 22.25h10q1.346 0 2.298-.952T20.25 19V8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-2.75 0-2.75-2.75v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.531.22q.105.106.162.243q.057.138.057.287v4q0 1.25 1.25 1.25h4q.149 0 .287.057t.243.163zM12 10.5q1.698 0 2.93.493q1.57.628 1.57 1.757v4.5q0 1.129-1.57 1.757q-1.232.493-2.93.493q-4.5 0-4.5-2.25v-4.5q0-2.25 4.5-2.25m3 3.979l-.07.028Q13.698 15 12 15q-1.902 0-3-.402v2.652Q9 18 12 18t3-.75z");
}

</style>
