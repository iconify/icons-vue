<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="restq01km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:content-paste-off" /></template>
<style>
.restq01km {
  fill: currentColor;
  d: path("m20 17.189l-1-1V5.616q0-.231-.192-.424T18.384 5H16v2.23h-5.958L6.812 4h3.44q.14-.586.623-.985q.483-.4 1.125-.4q.654 0 1.134.4q.48.398.62.985h4.63q.672 0 1.144.472T20 5.616zM12.578 5q.23-.23.23-.578t-.23-.578t-.578-.23t-.578.23t-.23.578t.23.578t.578.23t.578-.23m4.995 14L5 6.427v11.958q0 .23.192.423t.423.192zM5.615 20q-.67 0-1.143-.472Q4 19.056 4 18.385V5.81q0-.095.01-.163q.01-.067.048-.163L2.74 4.167l.713-.713l17.092 17.092l-.713.714l-1.317-1.318q-.097.039-.164.048t-.163.01z");
}

</style>
