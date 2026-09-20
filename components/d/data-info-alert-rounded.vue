<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzma8cc7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:data-info-alert-rounded" /></template>
<style>
.xzma8cc7p {
  fill: currentColor;
  d: path("M4.5 19.5q-.213 0-.356-.144T4 18.999t.144-.356t.356-.143h10q.213 0 .356.144t.144.357t-.144.356t-.356.143zm8.318-8.315Q11.5 9.869 11.5 8.002t1.316-3.185T15.997 3.5q1.867 0 3.185 1.316Q20.5 6.13 20.5 7.997t-1.315 3.185t-3.182 1.318t-3.185-1.315M4.5 11.5q-.213 0-.356-.144T4 10.999t.144-.356t.356-.143h4.56q.212 0 .356.142q.143.14.143.35q0 .197-.143.352t-.357.156zm0 4q-.213 0-.356-.144T4 14.999t.144-.356t.356-.143h8.579q.212 0 .356.142q.144.14.144.35q0 .197-.131.352t-.37.156zm11.773-4.73q.112-.116.112-.27V7.692q0-.153-.112-.269q-.111-.115-.273-.115t-.273.115t-.111.27V10.5q0 .154.111.27q.112.114.273.114t.273-.115m.077-4.727q.15-.15.15-.35t-.15-.35t-.35-.15t-.35.15t-.15.35t.15.35t.35.15t.35-.15");
}

</style>
