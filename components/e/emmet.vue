<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<circle class="cqrnwibuy"/><path class="rcw11zy8g"/><path class="wmvhi1shx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:emmet" /></template>
<style>
.cqrnwibuy {
  cx: 127.555px;
  cy: 128.184px;
  r: 127.555px;
  fill: var(--svg-color--1c1c20, #1c1c20);
}

.rcw11zy8g {
  fill: var(--svg-color--baffa9, #baffa9);
  d: path("m178.496 124.737l-14.205-14.205l7.306-30.035l-30.441 6.9l-13.8-13.8l68.187-17.047z");
}

.wmvhi1shx {
  fill: var(--svg-color--7acb16, #7acb16);
  d: path("M154.956 218.901L33.192 97.138L101.38 80.09l13.8 13.8l-48.706 12.176l27.6 27.6l32.064-7.712l-8.117 31.658l27.6 27.6l12.176-48.705l14.205 14.206z");
}

</style>
