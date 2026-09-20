<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="vz7uodsqg"/><path class="at0l2ccaw"/><path class="zj5h_ebhe"/><path class="mch2_mb8m"/><path class="jio7rkbex"/><path class="ynl4fg25g"/><path class="f_68y7f_p"/><path class="qib4-gbbu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:egg-background" /></template>
<style>
.at0l2ccaw {
  fill: var(--svg-color--87ffff, #87ffff);
  d: path("M17.548 16.202c.3-.744.453-1.539.452-2.341C18 10.47 16.025 4 12 4C9.392 4 7.645 6.715 6.738 9.549z");
}

.f_68y7f_p {
  fill: var(--svg-color--3e91ff, #3e91ff);
  d: path("m7.51 17.916l6.978-3.598l-5.527-3.402z");
}

.ft5dv1b6b {
  fill: none;
}

.jio7rkbex {
  fill: var(--svg-color--43c6fd, #43c6fd);
  d: path("M18 13.86c0 .83-.161 1.62-.452 2.342l-3.049-1.877V4.948c2.345 1.924 3.5 6.32 3.5 8.913");
}

.mch2_mb8m {
  fill: var(--svg-color--91dcf1, #91dcf1);
  d: path("M6.739 9.548C6.245 11.09 6 12.666 6 13.861c0 1.56.57 2.986 1.508 4.07l1.453-7.015z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qib4-gbbu {
  fill: var(--svg-color--0096ff, #0096ff);
  d: path("M14.5 19.444v-5.119l3.048 1.877a6.1 6.1 0 0 1-3.049 3.242");
}

.vz7uodsqg {
  fill: var(--svg-color--0075ff, #0075ff);
  d: path("M18 13.861C18 17.251 15.313 20 12 20s-6-2.748-6-6.139S7.974 4 12 4s6 6.47 6 9.861");
}

.ynl4fg25g {
  fill: var(--svg-color--44b5fd, #44b5fd);
  d: path("M18 13.861c0 .83-.16 1.62-.452 2.341l-3.066-1.887l3.397-2.062c.08.58.12 1.125.12 1.608");
}

.zj5h_ebhe {
  fill: var(--svg-color--aff, #aff);
  d: path("m10.308 4.414l-1.347 6.503L6.738 9.55c.695-2.17 1.882-4.27 3.57-5.135");
}

</style>
