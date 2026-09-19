<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gy6zi6cjg"/><circle class="chv9dne5y"/><circle class="dkrsg2bur"/><circle class="vzrnk1znj"/><path class="izub7qbym"/><path class="v4t20va7b"/><path class="z-x76cbby"/><path class="luv8qfy5b"/><path class="r89whfx4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:caynaxsportstracker" /></template>
<style>
.chv9dne5y {
  cx: 12.522px;
  cy: 14.802px;
  r: 2.308px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dkrsg2bur {
  cx: 21.248px;
  cy: 14.802px;
  r: 2.308px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gy6zi6cjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.007 3.46a10.41 10.41 0 0 0-10.41 10.41a9.2 9.2 0 0 0 .744 3.864c2.275 4.335 6.608 10.372 9.735 15.089c2.786-4.658 7.992-11.114 9.594-15.09A10.404 10.404 0 0 0 17.007 3.46");
}

.izub7qbym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.522 15.065a9.2 9.2 0 0 0 .463-3.57l-2.375-.247c-1.176-.392.17-2.465 1.592-3.476c.992-.481 1.103.192 1.381.637a2.3 2.3 0 0 0 1.828 1.635c.983.055 1.789-.3 1.74 1.02a10.1 10.1 0 0 1-8.353 3.759");
}

.luv8qfy5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.05 37.1l-7.375-8.291l-10.294-1.088");
}

.r89whfx4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.577 3.476a21.511 21.511 0 1 1-10.5 7.26");
}

.v4t20va7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("m21.215 15.101l-.065-4.037");
}

.vzrnk1znj {
  cx: 18.986px;
  cy: 6.721px;
  r: 0.75px;
  fill: currentColor;
}

.z-x76cbby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.806 33.693l12.27-.87l13.904-11.48l14.05-1.44");
}

</style>
