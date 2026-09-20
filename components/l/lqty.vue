<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="clfjdob4d"/><path class="u393u2jzw"/><path clip-rule="evenodd" class="o8ujd4b5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lqty" /></template>
<style>
.clfjdob4d {
  fill: var(--svg-color--2eb6ea, #2eb6ea);
  d: path("M10.636 19.636a7.636 7.636 0 1 0 0-15.273a7.636 7.636 0 0 0 0 15.273");
}

.ft5dv1b6b {
  fill: none;
}

.o8ujd4b5t {
  fill: var(--svg-color--745ddf, #745ddf);
  fill-rule: evenodd;
  d: path("M17.868 14.457c-1.158 2.965-3.875 5.082-7.231 5.176q.118.004.238.004H21s-.135-3.633-3.132-5.18");
}

.u393u2jzw {
  fill: var(--svg-color--1542cd, #1542cd);
  d: path("M10.675 19.627c-7.662 0-10.686-9.986-3.918-14.194c-.805 8.346 3.476 8.53 7.45 8.346c6.657-.31 6.662 5.848 6.662 5.848z");
}

</style>
