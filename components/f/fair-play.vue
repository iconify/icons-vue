<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2nodv-uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fair-play" /></template>
<style>
.r2nodv-uj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.881 10.25H20.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5.309q.28 1.909-.756 3.667q-1.297 2.204-3.802 2.716q-2.505.513-4.564-1.004q-2.058-1.517-2.311-4.061q-.238-2.399 1.278-4.218q-2.635-4.529-1.755-7.501Q4.199 1.75 8 1.75q3.678 0 4.297 2.972q.488 2.343-1.416 5.528m-4.723 1.041q1.285-.936 2.94-1.03q2.154-3.198 1.73-5.233Q10.458 3.25 8 3.25q-2.681 0-3.281 2.026q-.671 2.264 1.439 6.015M7.25 16q0 2.25 2.25 2.25T11.75 16T9.5 13.75T7.25 16");
}

</style>
