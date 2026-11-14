<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxhdyeb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:git-modified" /></template>
<style>
.dxhdyeb6g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75H7q-1.346 0-2.298.952T3.75 5v14q0 1.346.952 2.298T7 22.25h6.765l-.008-.007Q12 20.485 12 18t1.757-4.243Q15.515 12 18 12q1.211 0 2.25.418V8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-2.75 0-2.75-2.75v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.531.22q.105.106.162.243q.057.138.057.287v4q0 1.25 1.25 1.25h4q.149 0 .287.057t.243.163zM13.25 18q0-1.968 1.391-3.359T18 13.25t3.359 1.391T22.75 18t-1.391 3.359T18 22.75t-3.359-1.391T13.25 18m1.5 0q0 3.25 3.25 3.25T21.25 18T18 14.75T14.75 18M18 20q-2 0-2-2t2-2t2 2t-2 2");
}

</style>
