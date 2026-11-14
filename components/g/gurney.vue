<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lun9y1psi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gurney" /></template>
<style>
.lun9y1psi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 8.25h1q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-2.537l-4.038 2.5l4.049 2.507Q19 18.365 19 20.25q0 2-2 2t-2-2q0-.876.384-1.368l-3.634-2.25l-3.734 2.312q.484.553.484 1.306q0 .828-.586 1.414T6.5 22.25q-2 0-2-2q0-1.885 1.776-1.993l4.049-2.507l-4.038-2.5H4.25q-1.036 0-1.768-.732T1.75 10.75q0-2.5 2.5-2.5V5.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5 4.75h13q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146zm-13 0h11.5v-2H5.75zm6 6.618l2.614-1.618H9.136z");
}

</style>
