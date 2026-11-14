<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2stu0bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:electoral-votes" /></template>
<style>
.r2stu0bic {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.25 11.25h.25q1.76 0 3.005 1.245T21.75 15.5V18q0 1.76-1.245 3.005T17.5 22.25h-11q-1.76 0-3.005-1.245T2.25 18v-2.5q0-1.76 1.245-3.005T6.5 11.25h.25V3.5q0-1.75 1.75-1.75h7q1.75 0 1.75 1.75zm-9 0h7.5V3.5q0-.25-.25-.25h-7q-.25 0-.25.25zm3.226-3.084L10.28 6.97q-.105-.106-.243-.163T9.75 6.75t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141T9 7.5t.014.146q.015.073.043.141t.069.13q.041.061.094.113l1.75 1.75q.105.106.243.163T11.5 10t.287-.057t.243-.163l.023-.023l2.75-3q.101-.11.152-.25t.044-.29q-.006-.149-.069-.284t-.173-.236q-.055-.05-.118-.088t-.132-.064q-.07-.025-.143-.036q-.073-.012-.147-.008q-.073.003-.145.02t-.139.049q-.067.031-.126.075q-.06.044-.11.098z");
}

</style>
