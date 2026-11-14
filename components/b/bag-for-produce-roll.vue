<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw5z0lbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bag-for-produce-roll" /></template>
<style>
.iw5z0lbza {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 4.75q0-2.5 4.25-2.5t4.25 2.5v3h9.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.177 0-.335-.079L18 20.589l-2.165 1.082q-.078.039-.163.059t-.172.02t-.172-.02t-.163-.059L13 20.589l-2.165 1.082q-.133.067-.282.077q-.149.011-.29-.036q-.142-.048-.254-.145q-.113-.098-.18-.232q-.079-.158-.079-.335v-1.912Q8.725 19.5 7 19.5q-4.25 0-4.25-2.5zm7 2.088V17q0 1-2.75 1t-2.75-1V6.838Q5.275 7.25 7 7.25t2.75-.412m10 2.412h-8.5v10.536l1.415-.707q.078-.039.163-.059T13 19t.172.02t.163.059l2.165 1.082l2.165-1.082q.078-.039.163-.059T18 19t.172.02t.163.059l1.415.707z");
}

</style>
