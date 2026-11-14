<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc4pddjnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:compound-path" /></template>
<style>
.jc4pddjnr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.25h9.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3.588q-.331-.088-.75-.088q-2 0-2 2t2 2t2-2q0-.351-.062-.641q1.881.364 3.411 1.749q2.304 2.087 2.381 5.195t-2.121 5.306t-5.306 2.121t-5.195-2.381q-1.385-1.53-1.749-3.411q.29.062.641.062q2 0 2-2t-2-2t-2 2q0 .419.088.75H5q-2.75 0-2.75-2.75V5q0-2.75 2.75-2.75");
}

</style>
