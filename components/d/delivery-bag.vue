<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhv545_ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:delivery-bag" /></template>
<style>
.fhv545_ot {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 7.25h-.25V6q0-2.25-2.25-2.25h-5Q7.25 3.75 7.25 6v1.25H7q-1.76 0-3.005 1.245T2.75 11.5V17q0 1.76 1.245 3.005T7 21.25h10q1.76 0 3.005-1.245T21.25 17v-5.5q0-1.76-1.245-3.005T17 7.25m4.25 5.25q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-17q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h17q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146m-6-5.25h-6.5V6q0-.75.75-.75h5q.75 0 .75.75z");
}

</style>
