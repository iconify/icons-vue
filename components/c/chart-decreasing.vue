<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="t8v0an0fk"/><path class="omgfyk3rt"/><path class="l34g7mbip"/><path class="a5jinkenu"/><path class="r9wo5nbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:chart-decreasing" /></template>
<style>
.a5jinkenu {
  fill: var(--svg-color--0b88cf, #0b88cf);
  d: path("m5.1 5.14l-.08 6.17l26.92 48.51l23.7-21.91l63.78 85.1h3.49l.14-5.16l-66.6-88.86l-23.02 21.28L8.45 5.11z");
}

.l34g7mbip {
  fill: none;
  stroke: var(--svg-color--b0bec5, #b0bec5);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M123.8 24.66H4.15m119.66 19.67H4.16M123.83 64H4.17m119.67 19.67H4.19m119.66 19.67H4.2");
}

.omgfyk3rt {
  fill: none;
  stroke: var(--svg-color--b0bec5, #b0bec5);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-993px, 1.993px);
  d: path("M24.7 4.2v119.6M44.35 4.2v119.6M64 4.2v119.6M83.65 4.2v119.6M103.3 4.2v119.6");
}

.r9wo5nbmc {
  fill: var(--svg-color--b0bec5, #b0bec5);
  d: path("M122.01 5.99V122H5.99V5.99zM124 4H4v120h120z");
}

.t8v0an0fk {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 4h120v120H4z");
}

</style>
