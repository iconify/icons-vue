<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8dbj7buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:emergency-drill" /></template>
<style>
.g8dbj7buo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 5.25q0-1.5.75-2.25t2.25-.75q3 0 3 3q0 1.709-.974 2.445l.627 1.378q.976-.331 2.1-.323H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v4q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5.328q.288 2.13-.907 4.051q-1.459 2.347-4.178 2.846t-4.916-1.176q-2.199-1.675-2.439-4.428t1.635-4.784q.556-.601 1.189-1.023l-.691-1.521q-.29.035-.615.035q-3 0-3-3M7 15q0 2.5 2.5 2.5T12 15t-2.5-2.5T7 15");
}

</style>
