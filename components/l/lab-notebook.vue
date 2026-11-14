<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkohr_bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lab-notebook" /></template>
<style>
.wkohr_bnn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 5v13.5q0 2.75 2.75 2.75h12q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 19.75H7q-1.25 0-1.25-1.25T7 17.25h12q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 2.25H7Q4.25 2.25 4.25 5m1.5 10.938V5q0-1.25 1.25-1.25h11.25v12H7q-.719 0-1.25.188M12 5.25h1q1.75 0 1.75 1.75v.711q0 .145.053.279l1.07 2.674q.444 1.109-.226 2.098q-.669.988-1.863.988h-2.568q-1.194 0-1.863-.988q-.67-.989-.226-2.098l1.07-2.675q.053-.133.053-.278V7q0-1.75 1.75-1.75");
}

</style>
