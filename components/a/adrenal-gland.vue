<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n46no5w8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:adrenal-gland" /></template>
<style>
.n46no5w8e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.76 5.563l-.474.016q1.305.214 2.136 1.002q1.278 1.21.806 3.101q-.007.028-.016.055q-.258.772-1.216 1.879q-.545.629-.792 1.134h4.046q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4.046q.247.505.792 1.134q.958 1.107 1.216 1.879q.009.027.016.055q.472 1.891-.806 3.101Q14.281 21.5 12.25 21.5q-3.112 0-5.107-2.395Q5.25 16.834 5.25 13.5t1.893-5.605q1.515-1.818 3.673-2.256q-.82-.118-1.087-1.009q-.321-1.067.63-1.645l1.242-.759q1.511-.924 2.764.329l.415.414q.706.704.34 1.632t-1.36.962");
}

</style>
