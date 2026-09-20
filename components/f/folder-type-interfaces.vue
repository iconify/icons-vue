<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y18sezb8e"/><path class="dg2cg9rap"/><path class="lnivpub5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-interfaces" /></template>
<style>
.dg2cg9rap {
  fill: var(--svg-color--fff, #fff);
  d: path("M31.239 18.461H23.3a3.458 3.458 0 1 0-1.874 4.612a3.97 3.97 0 0 0 2.018-1.729h7.789a8.3 8.3 0 0 1 .006-2.883m-11.108 3.026a1.585 1.585 0 1 1 1.585-1.587a1.584 1.584 0 0 1-1.585 1.587");
}

.lnivpub5c {
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M25.239 13.951a7.909 7.909 0 1 0 .772 10.965");
}

.y18sezb8e {
  fill: var(--svg-color--a4b100, #a4b100);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

</style>
