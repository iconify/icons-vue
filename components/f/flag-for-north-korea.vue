<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ajyp11b8r"/><path class="cyi8qyruo"/><path class="kkabu6bhb"/><path class="ikvkj5f-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-north-korea" /></template>
<style>
.ajyp11b8r {
  fill: var(--svg-color--024fa2, #024fa2);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.cyi8qyruo {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 9h36v1H0zm0 17h36v1H0z");
}

.ikvkj5f-x {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.278 23.778a5.778 5.778 0 1 0 0-11.556a5.778 5.778 0 0 0 0 11.556m-1.257-7.508l1.257-3.868l1.257 3.868h4.067l-3.29 2.39l1.257 3.868l-3.29-2.39l-3.29 2.39l1.257-3.868l-3.29-2.39z");
}

.kkabu6bhb {
  fill: var(--svg-color--ed1c27, #ed1c27);
  d: path("M0 10h36v16H0z");
}

</style>
