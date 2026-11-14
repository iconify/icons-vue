<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duzsrvhhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:battery-warning-car" /></template>
<style>
.duzsrvhhn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.25 5.25h-4.5V3.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q9.074 2.75 9 2.75H5.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v1.926q-.978.292-1.755 1.069Q1.75 7.74 1.75 9.5v8q0 1.76 1.245 3.005T6 21.75h12q1.76 0 3.005-1.245T22.25 17.5v-8q0-1.76-1.245-3.005q-.777-.777-1.755-1.069V3.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014H15q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146zm-6 0h-2v-1h2zm7.5 0v-1h2v1zm-1.587 5.74l2.465 4.257q.724 1.25.003 2.501Q15.909 19 14.465 19h-4.93q-1.444 0-2.166-1.252q-.721-1.251.003-2.501l2.465-4.257Q10.56 9.744 12 9.744t2.163 1.246");
}

</style>
