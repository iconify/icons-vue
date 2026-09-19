<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jhb2-ebos"/><path class="fvfok-bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:down-button" /></template>
<style>
.fvfok-bkj {
  fill: var(--svg-color--fff, #fff);
  d: path("M53.36 21.348c-.197-2.854-1.442-5.237-3.149-6.281h-34.07c-1.711 1.049-2.962 3.438-3.149 6.297l20.11 27.619l20.255-27.635");
}

.jhb2-ebos {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M64 57.1a6.9 6.9 0 0 1-6.897 6.903H6.893A6.9 6.9 0 0 1-.003 57.1V6.9c0-3.81 3.088-6.9 6.896-6.9h50.21C60.913 0 64 3.09 64 6.9z");
}

</style>
