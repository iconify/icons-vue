<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zkdrj_vww"/><path class="itn4s7azx"/><path class="g887gz_5j"/><path class="x4j9odtxo"/><path class="ews7hr49h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-csharp2" /></template>
<style>
.ews7hr49h {
  fill: var(--svg-color--fff, #fff);
  d: path("M27.67 15.271v-1.238h-1.007v-1.006h-1.239v1.006h-1.508v-1.006h-1.239v1.006h-1.008v1.238h1.006v1.513h-1.006v1.237h1.006v1.006h1.239v-1.006h1.509v1.006h1.239v-1.006h1.006v-1.237h-1v-1.513Zm-2.246 1.513h-1.508v-1.513h1.508Z");
}

.g887gz_5j {
  fill: var(--svg-color--1a7515, #1a7515);
  d: path("M28.549 23.171L16 16L3.451 23.171a2.4 2.4 0 0 0 .809.72c2.056 1.141 8.954 4.927 10.332 5.706a2.64 2.64 0 0 0 2.763.026q5.19-2.871 10.386-5.733a2.4 2.4 0 0 0 .808-.719");
}

.itn4s7azx {
  fill: var(--svg-color--358230, #358230);
  d: path("M28.549 23.171a2 2 0 0 0 .147-.182a2.4 2.4 0 0 0 .3-1.22V10.232a2.4 2.4 0 0 0-.318-1.244c-.036-.059-.089-.105-.13-.16L16 16Z");
}

.x4j9odtxo {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.6 18.02a4.121 4.121 0 1 1-.027-4.087l3.615-2.073A8.309 8.309 0 0 0 7.7 16a8.2 8.2 0 0 0 1.1 4.117a8.319 8.319 0 0 0 14.411-.017z");
}

.zkdrj_vww {
  fill: var(--svg-color--4e994a, #4e994a);
  d: path("M29 10.232a2.4 2.4 0 0 0-.318-1.244a2.45 2.45 0 0 0-.936-.879q-5.194-2.868-10.393-5.733a2.64 2.64 0 0 0-2.763.024c-1.378.779-8.275 4.565-10.331 5.706A2.29 2.29 0 0 0 3 10.231V21.77a2.4 2.4 0 0 0 .3 1.22a2.43 2.43 0 0 0 .954.9c2.056 1.141 8.954 4.927 10.332 5.706a2.64 2.64 0 0 0 2.763.026q5.19-2.871 10.386-5.733a2.44 2.44 0 0 0 .955-.9a2.4 2.4 0 0 0 .3-1.22V10.232");
}

</style>
