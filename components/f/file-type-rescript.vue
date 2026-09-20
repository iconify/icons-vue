<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGrHj4zbyn" x1="11.421" x2="21.509" y1="-221.705" y2="-248.792" gradientTransform="matrix(1 0 0 -1 0 -218)" gradientUnits="userSpaceOnUse"><stop offset="0" class="dxg-z6ffr"/><stop offset=".409" class="wosxotb5b"/><stop offset=".999" class="k487vmbmu"/></linearGradient></defs><path fill="url(#SVGrHj4zbyn)" class="j92gy1blq"/><path class="gltpgtbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-rescript" /></template>
<style>
.dxg-z6ffr {
  stop-color: var(--svg-color--e84f4f, #e84f4f);
}

.gltpgtbxf {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.974 15.554a3.325 3.325 0 1 0-3.324-3.325a3.325 3.325 0 0 0 3.324 3.325M9.316 11.809a4.7 4.7 0 0 1 .206-1.987A1.9 1.9 0 0 1 10.345 9a4.7 4.7 0 0 1 1.987-.205h2.64v12.25a4.7 4.7 0 0 1-.144 1.664a1.9 1.9 0 0 1-1.02 1.02a4.7 4.7 0 0 1-1.664.143a4.7 4.7 0 0 1-1.664-.143a1.9 1.9 0 0 1-1.02-1.02a4.7 4.7 0 0 1-.143-1.664Z");
}

.j92gy1blq {
  d: path("M2 10.97c0-3.738 0-5.6.952-6.916a5 5 0 0 1 1.1-1.1C5.364 2 7.233 2 10.969 2H21.03c3.738 0 5.605 0 6.916.951a5 5 0 0 1 1.1 1.1C30 5.364 30 7.232 30 10.97v10.06c0 3.737 0 5.605-.952 6.916a5 5 0 0 1-1.1 1.1C26.636 30 24.768 30 21.03 30H10.969c-3.736 0-5.6 0-6.915-.952a5 5 0 0 1-1.1-1.1C2 26.636 2 24.767 2 21.03Z");
}

.k487vmbmu {
  stop-color: var(--svg-color--cb3939, #cb3939);
}

.wosxotb5b {
  stop-color: var(--svg-color--db4646, #db4646);
}

</style>
