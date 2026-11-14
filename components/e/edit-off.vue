<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtd4c_g-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:edit-off" /></template>
<style>
.wtd4c_g-d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m15.748 5.848l-4.065 4.066l-4.597-4.597l4.066-4.065q.659-.66 1.591-.66t1.591.66l1.414 1.414q.66.659.66 1.591t-.66 1.591m-9.094 9.094l2.2-2.199l-4.597-4.597l-2.199 2.199q-.413.413-.573.974l-.6 2.101q-.353 1.233.554 2.141q.908.907 2.141.554l2.101-.6q.561-.16.973-.573");
}

</style>
