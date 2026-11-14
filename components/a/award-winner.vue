<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy8ufxh_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:award-winner" /></template>
<style>
.qy8ufxh_p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.75h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.25h1q3 0 3 3t-3 3h-1.256q-.4 1.288-1.428 2.316q-1.413 1.412-3.316 1.64v2.544h1.5q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-4.5q-1.036 0-1.768-.732T7.25 19.75q0-2.5 2.5-2.5h1.5v-2.544q-1.903-.228-3.316-1.64q-1.028-1.028-1.428-2.316H5.25q-1.5 0-2.25-.75t-.75-2.25q0-3 3-3h1V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 2.75 7 2.75m-.75 3.5h-1q-1.5 0-1.5 1.5q0 .75.375 1.125t1.125.375h1.005Q6.25 9.126 6.25 9zm12.5 0h-1V9q0 .126-.005.25h1.005q1.5 0 1.5-1.5t-1.5-1.5");
}

</style>
