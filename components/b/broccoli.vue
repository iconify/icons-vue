<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6kzb3bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:broccoli" /></template>
<style>
.m6kzb3bwk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.131 11.218q.297 2.379 2.569 2.523q1.216 1.01 3.435.95l-.876 5.695q-.012.073-.008.147q.003.074.021.145q.017.072.048.139q.032.067.075.127q.044.059.098.109t.118.088q.063.039.133.064q.069.025.142.036q.057.009.114.009h6q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.057-.009-.114l-.902-5.865q.423-.027.84-.093q2.368-.373 2.954-1.942q2.143-1.441 1.117-3.787q-.9-2.055-3.083-2.015q-.399-1.808-2.7-2.293q-2.209-.465-3.534.95q-1.332-1.099-3.245-.423q-2.211.78-2.417 3.091q-1.917.998-1.64 3.209");
}

</style>
