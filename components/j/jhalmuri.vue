<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmzrv_xzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:jhalmuri" /></template>
<style>
.wmzrv_xzm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.956 4.861Q19.75 5.966 19.75 8.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 7.75H5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0-2.534 1.794-3.639q1.319-.811 2.574-.386Q9.64 2.5 12 2.5t3.382 1.975q1.255-.425 2.574.386m-6.849 13.67l-1.25 2.083q-.107.178-.107.386q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3q.208 0 .386-.107q.063-.038.118-.088t.099-.109t.075-.126q.032-.066.05-.138t.021-.146t-.007-.146t-.036-.143t-.063-.133l-1.25-2.083l6.721-9.6q-.052.074-.12.133t-.148.101t-.168.064T19 9.25H5q-.09 0-.178-.021t-.168-.064q-.08-.041-.148-.101q-.068-.059-.12-.133z");
}

</style>
