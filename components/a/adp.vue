<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#tokenBrandedAdp0)" class="lwi7k5f1z"/><path fill="url(#tokenBrandedAdp1)" class="na6jc7_cy"/><defs><linearGradient id="tokenBrandedAdp0" x1="6.561" x2="17.432" y1="3.527" y2="20.27" gradientUnits="userSpaceOnUse"><stop class="v98oowq_g"/><stop offset="1" class="f7agvcbvv"/></linearGradient><linearGradient id="tokenBrandedAdp1" x1="6.56" x2="17.431" y1="3.527" y2="20.27" gradientUnits="userSpaceOnUse"><stop class="v98oowq_g"/><stop offset="1" class="f7agvcbvv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:adp" /></template>
<style>
.f7agvcbvv {
  stop-color: var(--svg-color--4587f1, #4587F1);
}

.ft5dv1b6b {
  fill: none;
}

.lwi7k5f1z {
  d: path("M13.052 3.248a1.193 1.193 0 0 0-2.1 0L2.14 20.098c-.131.243-.163.5-.125.73c2.93.838 7.65.47 9.987-3.956c2.062-3.918 3.275-6.074 4.031-7.43l.137-.238l-3.118-5.95z");
}

.na6jc7_cy {
  d: path("m16.42 9.685l-3.825 7.187a6.78 6.78 0 0 0 6.656 4.5c1.156 0 2.05-.206 2.725-.5c.05-.25.025-.518-.106-.775z");
}

.v98oowq_g {
  stop-color: var(--svg-color--3e64df, #3E64DF);
}

</style>
