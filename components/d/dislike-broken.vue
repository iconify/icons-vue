<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z_plnwe8g"/><path class="lmh6yib_l"/><path class="v0-4-h-2h"/><path class="eymym15ry"/><path class="due70sa8a"/><path class="x555n9v5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dislike-broken" /></template>
<style>
.due70sa8a {
  d: path("M13.9951 18.7786L13.3325 14.734C13.2493 14.2267 13.6404 13.7658 14.1539 13.7658H19.335");
}

.eymym15ry {
  d: path("M8.59609 2C7.73231 2 7.01201 2.66139 6.93752 3.52293L6.12535 12.9156C6.07919 13.4494 6.29223 13.973 6.69789 14.3225L8.13663 15.5623C8.80416 16.1375 9.44635 16.7598 9.8617 17.5374C10.146 18.0695 10.3664 18.6328 10.5178 19.2163L10.9935 21.0501C11.0856 21.4053 11.3342 21.7039 11.6739 21.8676C11.9826 22.0163 12.3399 22.0408 12.6673 21.9356L12.8123 21.8891C13.354 21.715 13.7659 21.2864 13.9044 20.7525");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lmh6yib_l {
  d: path("M3 13.7658L3.9716 2.52928C3.99621 2.24466 3.77207 2 3.48671 2C3.21791 2 3 2.21815 3 2.48726");
}

.v0-4-h-2h {
  d: path("M13.9946 18.7786C14.1022 19.4356 14.0715 20.108 13.9043 20.7525");
}

.x555n9v5n {
  d: path("M19.3351 13.7658C20.3681 13.7658 21.1517 12.8338 20.9755 11.8148L20.27 7.73505C19.6976 4.42561 16.7266 2 13.2453 2H8.59668");
}

.z_plnwe8g {
  d: path("M3 2.48726V13.7658");
}

</style>
