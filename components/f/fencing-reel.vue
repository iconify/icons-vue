<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwxn9-bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fencing-reel" /></template>
<style>
.vwxn9-bmh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 10.5q0-6.591 2.351-7.577q.413-.173.899-.173q2.184 0 2.9 3.5h8.2q.557-2.721 2.001-3.327q.413-.173.899-.173q3.25 0 3.25 7.75T19 18.25q-2.184 0-2.9-3.5h-1.85V17q0 2.25 2.25 2.25h.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.5q-3.75 0-3.75-3.75v-2.25H7.9q-.716 3.5-2.9 3.5q-3.25 0-3.25-7.75m12.5 2.75h1.626q-.126-1.225-.126-2.75t.126-2.75H14.25zm-1.5-5.5h-1.5v5.5h1.5zm-4.626 0q.126 1.225.126 2.75t-.126 2.75H9.75v-5.5z");
}

</style>
