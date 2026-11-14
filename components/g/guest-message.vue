<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcsfrh0uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:guest-message" /></template>
<style>
.jcsfrh0uk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 5.5q0-1.346.952-2.298T5.5 2.25h13q1.346 0 2.298.952T21.75 5.5v10q0 1.346-.952 2.298t-2.298.952h-7.218l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.75H5.5q-3.25 0-3.25-3.25zM12 5.25Q9.25 5.25 9.25 8T12 10.75T14.75 8T12 5.25M12 12q-4.75 0-4.75 3q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T8.75 15q0-1.5 3.25-1.5t3.25 1.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3-4.75-3");
}

</style>
