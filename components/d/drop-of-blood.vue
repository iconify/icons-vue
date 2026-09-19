<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iHWCsbc)" class="xeke6bb2l"/><path fill="url(#iOXaQPb)" class="xeke6bb2l"/><path fill="url(#ixM8jib)" class="xeke6bb2l"/><path fill="url(#iBczRob)" class="xeke6bb2l"/><path fill="url(#iuScqde)" class="xeke6bb2l"/><defs><radialGradient id="iOXaQPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 17.2646 -15.1956 0 16 12.767)" gradientUnits="userSpaceOnUse"><stop offset=".901" class="o6f-xfx9z"/><stop offset="1" class="q_y2i0b2a"/></radialGradient><radialGradient id="ixM8jib" cx="0" cy="0" r="1" gradientTransform="matrix(-8.28031 6.06516 -3.80655 -5.1968 23.378 18.199)" gradientUnits="userSpaceOnUse"><stop class="ca2_496fa"/><stop offset="1" class="rgw0_hbim"/></radialGradient><radialGradient id="iBczRob" cx="0" cy="0" r="1" gradientTransform="matrix(7.17264 13.44897 -6.63395 3.53803 20.266 3.96)" gradientUnits="userSpaceOnUse"><stop class="tdag0bcgo"/><stop offset="1" class="jdkvfvb1d"/></radialGradient><linearGradient id="iHWCsbc" x1="16" x2="16" y1="8.75" y2="29.25" gradientUnits="userSpaceOnUse"><stop class="lu3c8ac2r"/><stop offset="1" class="d-b1w25hu"/></linearGradient><linearGradient id="iuScqde" x1="9.313" x2="16" y1="10.75" y2="13" gradientUnits="userSpaceOnUse"><stop offset=".032" class="x7luimn5g"/><stop offset="1" class="migybnbkr"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:drop-of-blood" /></template>
<style>
.ca2_496fa {
  stop-color: var(--svg-color--ff6b8d, #FF6B8D);
}

.d-b1w25hu {
  stop-color: var(--svg-color--ff1f5d, #FF1F5D);
}

.ft5dv1b6b {
  fill: none;
}

.jdkvfvb1d {
  stop-color: var(--svg-color--ff60ab, #FF60AB);
  stop-opacity: 0;
}

.lu3c8ac2r {
  stop-color: var(--svg-color--ff2a85, #FF2A85);
}

.migybnbkr {
  stop-color: var(--svg-color--e5254f, #E5254F);
  stop-opacity: 0;
}

.o6f-xfx9z {
  stop-color: var(--svg-color--ff5ab2, #FF5AB2);
  stop-opacity: 0;
}

.q_y2i0b2a {
  stop-color: var(--svg-color--ff5ab2, #FF5AB2);
}

.rgw0_hbim {
  stop-color: var(--svg-color--ff6b8d, #FF6B8D);
  stop-opacity: 0;
}

.tdag0bcgo {
  stop-color: var(--svg-color--ff60ab, #FF60AB);
}

.x7luimn5g {
  stop-color: var(--svg-color--af4963, #AF4963);
}

.xeke6bb2l {
  d: path("M7.283 14.94L13.9 3.322a2.466 2.466 0 0 1 4.292.011l6.738 11.97h-.011a10 10 0 0 1 1.143 4.665c0 5.557-4.505 10.062-10.062 10.062S5.938 25.526 5.938 19.97c0-1.742.442-3.38 1.22-4.808h-.002l.063-.11z");
}

</style>
