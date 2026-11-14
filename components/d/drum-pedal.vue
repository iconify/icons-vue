<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcawdibyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drum-pedal" /></template>
<style>
.zcawdibyn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 5.5q0-3.75 3.75-3.75t3.75 3.75q0 3.244-2.806 3.682l2.642 10.568H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3q-.109 0-.213-.031t-.196-.09t-.162-.142t-.114-.182q-.061-.137-.065-.286V20.5q0-.139.05-.269q.054-.139.156-.248t.239-.168l.001-.001l12.924-5.743l-1.212-4.846Q11.25 8.941 11.25 5.5m5.789 14.25l-1.05-4.202l-9.455 4.202z");
}

</style>
