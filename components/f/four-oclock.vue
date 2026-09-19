<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g transform="scale(.99701 .99699)"><circle class="ghn-mubpt"/><path class="mrjhw5b0q"/><path class="dwgf8g2yz"/><path class="ykvwol_4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:four-oclock" /></template>
<style>
.dwgf8g2yz {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M33.979 11.07c0-1.444-.852-2.613-1.896-2.613c-1.046 0-1.896 1.169-1.896 2.613v21.15c0 1.444.85 2.612 1.896 2.612c1.044 0 1.896-1.168 1.896-2.612z");
}

.ghn-mubpt {
  cx: 32.09px;
  cy: 32.1px;
  r: 29.733px;
  fill: var(--svg-color--e0e7ec, #e0e7ec);
}

.mrjhw5b0q {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M0 32.1c0 17.697 14.397 32.1 32.09 32.1c17.699 0 32.1-14.398 32.1-32.1C64.189 14.402 49.79 0 32.09 0C14.394 0 0 14.399 0 32.1m6.249 0c0-14.251 11.595-25.846 25.844-25.846c14.253 0 25.851 11.595 25.851 25.846c0 14.254-11.598 25.848-25.851 25.848c-14.249 0-25.844-11.593-25.844-25.848");
}

.ykvwol_4l {
  fill: var(--svg-color--788288, #788288);
  d: path("M43.532 44.08c1.144.877 2.589.917 3.227.088s.228-2.217-.915-3.098l-12.13-9.331c-1.142-.879-2.589-.917-3.225-.088s-.23 2.216.911 3.097l12.13 9.332");
}

</style>
