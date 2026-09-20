<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="iosn6wdio"/><path fill="url(#SVGMJWoeeJe)" class="l2-injb9l"/><defs><linearGradient id="SVGMJWoeeJe" x1="16.364" x2="7.908" y1="9" y2="9" gradientUnits="userSpaceOnUse"><stop class="j3jm16bcf"/><stop offset="1" class="nd4krubmk"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dafi" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iosn6wdio {
  fill: var(--svg-color--33363c, #33363c);
  fill-rule: evenodd;
  d: path("M16.91 3a1.09 1.09 0 0 0-1.091 1.091v3.84a7.092 7.092 0 1 0 3.273 5.98V4.09A1.09 1.09 0 0 0 18 3zm-1.091 10.91a3.819 3.819 0 1 0-7.638 0a3.819 3.819 0 0 0 7.638 0");
}

.j3jm16bcf {
  stop-color: var(--svg-color--222529, #222529);
}

.l2-injb9l {
  d: path("M12 6.818a7.07 7.07 0 0 1 3.819 1.113v5.434h-.039a3.819 3.819 0 0 0-7.56 0H4.93A7.09 7.09 0 0 1 12 6.818");
}

.nd4krubmk {
  stop-color: var(--svg-color--131519, #131519);
  stop-opacity: 0;
}

</style>
