<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jk0fi13mn"/><path class="q1bfiv0fc"/><path class="dct7vubdx"/><path class="s9bogabla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-curacao" /></template>
<style>
.dct7vubdx {
  fill: var(--svg-color--002b7f, #002b7f);
  d: path("M32 5H4a4 4 0 0 0-4 4v12h36V9a4 4 0 0 0-4-4M4 9.764l-1.176.854l.449-1.382l-1.175-.854h1.453L4 7l.449 1.382h1.453l-1.175.854l.449 1.382zm5.567 5.393L8 14.019l-1.567 1.139l.599-1.843l-1.567-1.139h1.937L8 10.333l.599 1.843h1.937l-1.567 1.139z");
}

.jk0fi13mn {
  fill: var(--svg-color--002b7f, #002b7f);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-2H0z");
}

.q1bfiv0fc {
  fill: var(--svg-color--f9e814, #f9e814);
  d: path("M0 21h36v4H0z");
}

.s9bogabla {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.599 12.176L8 10.333l-.599 1.843H5.464l1.567 1.139l-.598 1.842L8 14.019l1.567 1.138l-.598-1.842l1.567-1.139zM5.902 8.382H4.449L4 7l-.449 1.382H2.098l1.175.854l-.449 1.382L4 9.764l1.176.854l-.449-1.382z");
}

</style>
