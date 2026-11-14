<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwbb99lur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ball-generic" /></template>
<style>
.mwbb99lur {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.78 4.72q-.08-.081-.181-.134t-.214-.074q-.112-.02-.225-.007t-.217.061Q7.888 1.75 12 1.75t7.057 2.816q-.104-.047-.217-.061t-.225.007t-.214.074t-.181.134Q15.188 7.752 15.188 12t3.032 7.28q.08.081.181.134t.214.074t.225.007t.217-.061Q16.112 22.25 12 22.25t-7.057-2.816q.146.066.307.066q.149 0 .287-.057t.243-.163Q8.813 16.248 8.813 12T5.78 4.72m13.654 14.337Q22.25 16.112 22.25 12t-2.816-7.057q.066.146.066.307q0 .149-.057.287t-.163.243Q16.688 8.373 16.688 12t2.592 6.22q.081.08.134.181t.074.214t.007.225t-.061.217M1.75 12q0-4.112 2.816-7.057q-.047.104-.061.217t.007.225q.021.113.074.214t.134.181Q7.313 8.373 7.313 12T4.72 18.22q-.081.08-.134.181t-.074.214q-.02.112-.007.225t.061.217Q1.75 16.112 1.75 12");
}

</style>
