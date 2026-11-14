<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="am646jnll"/><path class="hgtjl3bcn"/><path class="khvluibsa"/><path class="fu2w26-4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flask-linear" /></template>
<style>
.am646jnll {
  d: path("M8.2002 3.4C8.2002 2.74 8.2002 2.4101 8.4052 2.205C8.6103 2 8.9402 2 9.6002 2H14.4002C15.0602 2 15.3901 2 15.5952 2.205C15.8002 2.4101 15.8002 2.74 15.8002 3.4C15.8002 4.06 15.8002 4.3899 15.5952 4.595C15.3901 4.8 15.0602 4.8 14.4002 4.8H9.6002C8.9402 4.8 8.6103 4.8 8.4052 4.595C8.2002 4.3899 8.2002 4.06 8.2002 3.4Z");
}

.fu2w26-4t {
  d: path("M10.2002 18.5H10.2003");
}

.hgtjl3bcn {
  d: path("M9.79986 4.80005V7.20005C9.79986 9.00005 8.39986 10.4 6.79986 12.8L4.39986 16.4C2.79986 18.8 4.19986 22 7.19986 22H16.7999C19.7999 22 21.1999 18.8 19.5999 16.4L17.1999 12.8C15.5999 10.4 14.1999 9.00005 14.1999 7.20005V4.80005");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.khvluibsa {
  d: path("M5.33301 15C7.79971 14.1 10.1997 14.1 11.9997 15C13.7997 15.9 16.1997 15.9 18.6664 15");
}

</style>
