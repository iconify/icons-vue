<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up3293b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bottle-return-coin" /></template>
<style>
.up3293b6g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 1.75h3q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3.189l3.28 3.281q.106.105.163.243t.057.287v4.019q-.693.352-1.286.945Q12 15.929 12 18t1.464 3.536q.163.162.333.307q-.564.407-1.297.407h-7q-2.25 0-2.25-2.25V9.5q0-.149.057-.287t.163-.243l3.28-3.281V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m9.5 12.5q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906");
}

</style>
