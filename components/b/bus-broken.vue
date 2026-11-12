<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d1fldo0no"/><path class="gunddzbpm"/><path class="qy9-4uicp"/><path class="jl627cb0x"/><path class="b50vfuvvv"/><path class="pquf2ubks"/><path class="ttqc2kbgo"/><path class="hyu4seb-a"/><path class="c0rq6rbus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bus-broken" /></template>
<style>
.b50vfuvvv {
  stroke-linejoin: round;
  d: path("M6 19.5V21C6 21.5523 6.44772 22 7 22H8.5C9.05228 22 9.5 21.5523 9.5 21V20");
}

.c0rq6rbus {
  d: path("M12 5H19.5M4.5 5H8.25");
}

.d1fldo0no {
  d: path("M10 2.00869C7.52043 2.04456 6.11466 2.22849 5.17157 3.17157C4 4.34315 4 6.22876 4 10V12C4 15.7712 4 17.6569 5.17157 18.8284C6.34315 20 8.22876 20 12 20C15.7712 20 17.6569 20 18.8284 18.8284C20 17.6569 20 15.7712 20 12V10C20 6.22876 20 4.34315 18.8284 3.17157C17.8853 2.22849 16.4796 2.04456 14 2.00869");
}

.gunddzbpm {
  stroke-linejoin: round;
  d: path("M12 13H4M20 13H16");
}

.hyu4seb-a {
  stroke-linejoin: round;
  d: path("M4 9H3C2.44772 9 2 9.44772 2 10V11C2 11.3148 2.14819 11.6111 2.4 11.8L4 13");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jl627cb0x {
  stroke-linejoin: round;
  d: path("M7 16H8.5");
}

.pquf2ubks {
  stroke-linejoin: round;
  d: path("M18 19.5V21C18 21.5523 17.5523 22 17 22H15.5C14.9477 22 14.5 21.5523 14.5 21V20");
}

.qy9-4uicp {
  stroke-linejoin: round;
  d: path("M15.5 16H17");
}

.ttqc2kbgo {
  stroke-linejoin: round;
  d: path("M20 9H21C21.5523 9 22 9.44772 22 10V11C22 11.3148 21.8518 11.6111 21.6 11.8L20 13");
}

</style>
