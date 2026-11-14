<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft_5wx5ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bar-stool-high" /></template>
<style>
.ft_5wx5ni {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.75 2.25h-7.5q-2 0-2 2q0 1.676 1.404 1.947l-1.1 8.523q-.054.135-.054.28q0 .047.006.094l-.75 5.81q-.019.148.02.292t.13.262t.221.192t.277.094q.073.009.147.004t.145-.024t.137-.052t.125-.078t.107-.101t.085-.12t.061-.134q.023-.07.033-.143l.69-5.346h8.132l.69 5.346q.01.073.033.143q.024.07.061.134q.036.064.085.12q.048.056.107.101t.125.078t.137.052t.145.024t.147-.004t.143-.033t.134-.061q.064-.036.12-.085q.056-.048.101-.107t.078-.125t.052-.137t.024-.145t-.004-.147l-.75-5.81q.006-.047.006-.094q0-.145-.054-.28l-1.1-8.523q1.404-.271 1.404-1.947q0-2-2-2m.123 12H8.127l1.032-8h5.682z");
}

</style>
