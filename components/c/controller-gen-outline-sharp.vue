<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w__4-eb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:controller-gen-outline-sharp" /></template>
<style>
.w__4-eb2k {
  fill: currentColor;
  d: path("M11.998 17.5q2.29 0 3.896-1.604t1.606-3.894t-1.604-3.896T12.003 6.5T8.106 8.104T6.5 11.998t1.604 3.896t3.894 1.606m-.002-1q-1.857 0-3.177-1.323T7.5 11.997t1.323-3.178t3.18-1.319t3.178 1.323t1.319 3.18t-1.323 3.178t-3.18 1.319M12 12.708l2.108-2.108l-.708-.708L11.292 12zM4 20V4h16v16zm1-1h14V5H5zM5 5v14z");
}

</style>
