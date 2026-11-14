<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfuv-ubow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hospital-chapel" /></template>
<style>
.gfuv-ubow {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.564 2.006Q15.25 5.075 15.25 7q0 2.631-2.5 2.955v.295h1q1.036 0 1.768.732t.732 1.768v7q0 .541-.2 1H19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5 20.75h2.95q-.2-.459-.2-1v-7q0-2.5 2.5-2.5h1v-.295Q8.75 9.631 8.75 7q0-1.925 2.686-4.994q.098-.112.232-.178q.133-.066.282-.076t.29.038q.142.047.254.146q.038.032.07.07");
}

</style>
