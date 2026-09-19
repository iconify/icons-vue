<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s09ijdb5a"/><path class="n6bl0cc3s"/><path class="j186jlbxj"/><path class="bsfn1-flc"/><path class="vl77qoo9e"/><path class="bz6lxox8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kid3" /></template>
<style>
.bsfn1-flc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.818 31.825c-1.963-3.46-3.168-4.651-5.294-3.905l2.509 6.968m4.912.256l8.637-2.361m-8.817-17.969q.25-.07.574-.164");
}

.bz6lxox8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.983 18.795a22 22 0 0 0-.5-.33");
}

.j186jlbxj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.55 23.206a22.3 22.3 0 0 0-.664-5.111c-1.922-7.43-7.135-12.521-11.683-11.376s-6.726 8.105-4.856 15.526a21.6 21.6 0 0 0 1.983 5.11m6.076 7.739a2.8 2.8 0 0 1 .643-.485a1.52 1.52 0 0 1 1.808.04c.554.554.355 1.652-.445 2.451s-1.897 1-2.45.445s-.355-1.651.444-2.45");
}

.n6bl0cc3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.83 9.12l-8.034 9.537a7.615 7.615 0 0 0 4.088 12.327l3.874.889m13.636-7.84a15.5 15.5 0 0 0-.454-4.606c-1.36-5.368-5.123-9.067-8.414-8.224s-4.87 5.858-3.51 11.19a15 15 0 0 0 1.887 4.533");
}

.s09ijdb5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.605 18.128a1.88 1.88 0 0 1 1.84.875a4.6 4.6 0 0 1 .828 1.735c.43 1.704-.068 3.3-1.112 3.563s-2.239-.905-2.668-2.61s.068-3.3 1.112-3.563m-4.667 9.865l25.391-6.932l2.31 8.461L43 34.511l-25.389 6.931z");
}

.vl77qoo9e {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 1.266 2.11;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.377 14.103c2.03-.469 4.384-.712 5.08.71c1.057 2.158-3.681 6.097-2.573 9.006a2.62 2.62 0 0 0 2.52 1.862c.983-.1 1.804-1.142 1.772-3.654a3.44 3.44 0 0 0-1.351-2.59");
}

</style>
