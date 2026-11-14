<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sovw1wr2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:architecture-diagram" /></template>
<style>
.sovw1wr2f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 1.75h2.75q3.182 0 3.364 3H17.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.75h.625q3.375 0 3.375 3.375v.75q0 3.375-3.375 3.375h-.625v2.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-6.261q-.182 3-3.364 3h-2.75q-3.375 0-3.375-3.375v-.75q0-3.375 3.375-3.375h2.75q3.182 0 3.364 3h5.511v-2h-.625q-3.375 0-3.375-3.375v-.75q0-3.375 3.375-3.375h.625v-2h-5.511q-.182 3-3.364 3h-2.75q-3.375 0-3.375-3.375v-.75q0-3.375 3.375-3.375");
}

</style>
