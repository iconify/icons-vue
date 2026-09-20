<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="axtfbxd2c"/><path class="fzbmm6b8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:asm" /></template>
<style>
.axtfbxd2c {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.717 2.132a1.76 1.76 0 0 1 1 2.34l-2.833 6.86h7.233c.753 0 1.453.64 1.74 1.306l3 6.887a1.76 1.76 0 0 1-1 2.333a1.887 1.887 0 0 1-2.434-.96l-2.546-6.233H8.33l-2.753 6.233c-.4.913-1.487 1.34-2.433.96a1.76 1.76 0 0 1-1-2.333L9.297 3.099c.393-.914 1.48-1.34 2.426-.96z");
}

.ft5dv1b6b {
  fill: none;
}

.fzbmm6b8o {
  fill: var(--svg-color--ffc301, #FFC301);
  d: path("M14.997 10.665a2.333 2.333 0 1 0 0-4.667a2.333 2.333 0 0 0 0 4.667");
}

</style>
