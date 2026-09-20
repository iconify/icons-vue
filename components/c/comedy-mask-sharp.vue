<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in5ha5bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:comedy-mask-sharp" /></template>
<style>
.in5ha5bnk {
  fill: currentColor;
  d: path("M14.344 15.306q.964-.983.964-2.364H8.673q0 1.381.973 2.364t2.354.983t2.344-.983M12.001 21q-1.664 0-3.12-.636q-1.454-.635-2.541-1.723T4.626 16.08T4 12.942V3h16v9.942q0 1.664-.626 3.138t-1.714 2.56t-2.54 1.724T12 21M7.577 9.27h3.23q0-.672-.479-1.154t-1.153-.482t-1.136.48t-.462 1.155m5.615-.019h3.231q0-.671-.475-1.143q-.476-.472-1.144-.472t-1.14.474t-.472 1.141");
}

</style>
