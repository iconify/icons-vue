<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGsrfSs5oU" x1="9.98" x2="123.28" y1="-831.352" y2="-945.122" gradientTransform="matrix(1 0 0 -1 -4 -826.11)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ibo9lk-wv"/><stop offset="1" class="ryjzwnfyj"/></linearGradient><path fill="url(#SVGsrfSs5oU)" class="i-9295bzu"/><path class="hua_2mbsm"/><path class="izjs16bix"/><path class="j6_15bbxq"/><path class="fri4tjbxu"/><path class="ojxgj-2fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:keycap-7" /></template>
<style>
.fri4tjbxu {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("m88.26 35.56l-27 61.2c-.3.67-.97 1.1-1.7 1.1h-8c-1.03.01-1.88-.81-1.89-1.85c0-.3.06-.59.19-.85l25.1-54.5a1.887 1.887 0 0 0-1.7-2.7h-30.9a1.9 1.9 0 0 1-1.9-1.9v-5.5c0-1.05.85-1.9 1.9-1.9h44.2c1.05 0 1.9.85 1.9 1.9v4.1c-.05.31-.11.61-.2.9");
}

.hua_2mbsm {
  fill: var(--svg-color--424242, #424242);
  d: path("M116.46 3.96h-104c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8v-104c0-4.42-3.58-8-8-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i-9295bzu {
  d: path("M116.46 123.96h-104c-4.42 0-8-3.58-8-8v-104c0-4.42 3.58-8 8-8h104c4.42 0 8 3.58 8 8v104c0 4.42-3.58 8-8 8");
}

.ibo9lk-wv {
  stop-color: var(--svg-color--81d4fa, #81d4fa);
}

.izjs16bix {
  fill: var(--svg-color--427687, #427687);
  d: path("M116.46 3.96h-104c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8v-104c0-4.42-3.58-8-8-8");
}

.j6_15bbxq {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M122.16 6.26a8.4 8.4 0 0 0-5.7-2.3h-104c-4.42 0-8 3.58-8 8v104c.02 2.12.84 4.16 2.3 5.7l16.8-16.8h76a5.91 5.91 0 0 0 5.9-5.9v-76z");
}

.ojxgj-2fp {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M40.16 12.86c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ryjzwnfyj {
  stop-color: var(--svg-color--0094d6, #0094d6);
}

</style>
