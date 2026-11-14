<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpsgxbcac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bell-pepper" /></template>
<style>
.lpsgxbcac {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 5.404q3.166-1.054 5.573.39Q21.25 7.55 21.25 12q0 10.25-5 10.25q-1.747 0-2.492-.934Q12.909 22 12 22t-1.758-.684q-.745.934-2.492.934q-5 0-5-10.25q0-4.45 2.927-6.206q2.407-1.444 5.573-.39V4.5q0-2.75 3.25-2.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043q-.072.014-.146.014q-1.75 0-1.75 1.25z");
}

</style>
