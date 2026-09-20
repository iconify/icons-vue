<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mherl3bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:content-paste-rounded" /></template>
<style>
.mherl3bez {
  fill: currentColor;
  d: path("M5.616 20q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h4.636q.14-.586.623-.985q.483-.4 1.125-.4q.654 0 1.134.4q.48.398.62.985h4.63q.672 0 1.144.472T20 5.616v12.769q0 .67-.472 1.143q-.472.472-1.143.472zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H16v1.423q0 .348-.23.578t-.578.23H8.808q-.348 0-.578-.23T8 6.423V5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192m6.963-13.999q.23-.23.23-.578t-.23-.578t-.578-.23t-.578.23t-.23.578t.23.578t.578.23t.578-.23");
}

</style>
