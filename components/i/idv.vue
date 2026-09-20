<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG1yMwudzi)" class="yok1td3nn"/><path fill="url(#SVGGukR9bPb)" class="jl7_p3bfh"/><path class="ia4csub5d"/><path clip-rule="evenodd" class="yzs4qlb5s"/><defs><linearGradient id="SVG1yMwudzi" x1="15.939" x2="16.587" y1="9.955" y2="13.261" gradientUnits="userSpaceOnUse"><stop class="uz0hvgb8m"/><stop offset=".66" class="jtsnowb9d"/></linearGradient><linearGradient id="SVGGukR9bPb" x1=".186" x2="3.687" y1="14.916" y2="8.834" gradientUnits="userSpaceOnUse"><stop class="lo1udbfhc"/><stop offset=".45" class="rkjmkbbuk"/><stop offset="1" class="li0ty-bbp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:idv" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ia4csub5d {
  fill: var(--svg-color--14b4fe, #14b4fe);
  d: path("M3.026 12.204A3.272 3.272 0 0 0 8.81 14.68l-.437-.793a2.455 2.455 0 0 1-4.521-1.682z");
}

.jl7_p3bfh {
  d: path("M17.729 15.887a3.273 3.273 0 1 0-2.516-5.367l.462.749a2.456 2.456 0 1 1-.401 1.264l-.655-.941c-.108.33-.163.675-.163 1.023v3.272h.818v-1.104a3.26 3.26 0 0 0 2.455 1.104");
}

.jtsnowb9d {
  stop-color: var(--svg-color--1a2c58, #1a2c58);
}

.li0ty-bbp {
  stop-color: var(--svg-color--5fc0f0, #5fc0f0);
}

.lo1udbfhc {
  stop-color: var(--svg-color--122543, #122543);
}

.rkjmkbbuk {
  stop-color: var(--svg-color--173c66, #173c66);
}

.uz0hvgb8m {
  stop-color: var(--svg-color--14b4fe, #14b4fe);
}

.yok1td3nn {
  d: path("M9.547 8.113h-.818v2.332a3.273 3.273 0 1 0 .082 4.23l-.438-.79a2.456 2.456 0 1 1 .323-1.68h.85z");
}

.yzs4qlb5s {
  fill: var(--svg-color--1ebcff, #1ebcff);
  fill-rule: evenodd;
  d: path("M12.001 15.887a3.273 3.273 0 1 0 0-6.545a3.273 3.273 0 0 0 0 6.545m0-.818a2.454 2.454 0 1 0 0-4.908a2.454 2.454 0 0 0 0 4.908");
}

</style>
