<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#tokenBrandedBondly0)" clip-rule="evenodd" class="jwg5hnpya"/><defs><linearGradient id="tokenBrandedBondly0" x1="18.158" x2="2.95" y1="4.143" y2="17.082" gradientUnits="userSpaceOnUse"><stop class="abw-cx94j"/><stop offset="1" class="qyekaeb-n"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bondly" /></template>
<style>
.abw-cx94j {
  stop-color: var(--svg-color--1352a2, #1352A2);
}

.ft5dv1b6b {
  fill: none;
}

.jwg5hnpya {
  fill-rule: evenodd;
  d: path("M5.959 5.559L3.177 7.176v9.471l2.747 1.647l4.311-2.547V20.9l1.836 1.1l8.753-5.353v-2.212l-4.112-2.53l4.111-2.558V6.971L12.071 2l-1.836 1.07V8.2zm6.63 8.906l1.752-1.094l4.13 2.452l-5.883 3.412zm0-5.077v-4.44l5.729 3.234l-4.018 2.294l-1.712-1.094zm-7.06-1.112v7.206l4.706-2.676v-1.841z");
}

.qyekaeb-n {
  stop-color: var(--svg-color--0d2e62, #0D2E62);
}

</style>
