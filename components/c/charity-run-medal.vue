<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brbiowbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:charity-run-medal" /></template>
<style>
.brbiowbtx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.889 8.848q1.12.509 2.062 1.451Q19.001 12.35 19 15.25q.001 2.9-2.049 4.951Q14.9 22.252 12 22.252t-4.951-2.051T5 15.25q-.001-2.9 2.049-4.951q.942-.942 2.062-1.451L5.365 2.9q-.079-.127-.104-.274t.008-.292q.033-.146.119-.267t.212-.202q.184-.115.4-.115h12q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .216-.115.4zm-4.301-.469q.679-.131 1.412-.131t1.412.131l3.229-5.129H7.359zM8.5 15.25q0 3.5 3.5 3.5t3.5-3.5t-3.5-3.5t-3.5 3.5");
}

</style>
