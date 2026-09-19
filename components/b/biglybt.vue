<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rc9e0ac8z"/><circle class="jlfa6jbpo"/><circle class="fk-0mtb1s"/><path class="fglakrbkp"/><path class="r-g_-cbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:biglybt" /></template>
<style>
.fglakrbkp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.285 20.136H21.49a2.946 2.946 0 0 1-2.946-2.946v-3.265a3.24 3.24 0 0 1 3.239-3.238h8.503z");
}

.fk-0mtb1s {
  cx: 38.896px;
  cy: 15.349px;
  r: 0.75px;
  fill: currentColor;
}

.jlfa6jbpo {
  cx: 34.797px;
  cy: 15.363px;
  r: 0.75px;
  fill: currentColor;
}

.r-g_-cbjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.385 17.764h5.358c.186 0 .337-.15.337-.336V13.44a.336.336 0 0 0-.337-.336h-5.358a.704.704 0 0 0-.705.704v3.251c0 .39.316.704.704.704");
}

.rc9e0ac8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.631 15.363h3.448m-8.758 3.821H8.988a14.8 14.8 0 0 0 3.09 5.746H8.095c-2.112 0-3.508 1.51-2.126 2.892L21.33 42.207a4.79 4.79 0 0 0 6.658-.109L42.01 28.08c1.42-1.42.017-3.15-2.157-3.15h-3.325a14.8 14.8 0 0 0 3.09-5.747l-9.333.001m0-7.643h9.333c-.749-2.724-2.28-5.148-4.35-7.041h0h-21.93c-2.07 1.893-3.601 4.317-4.35 7.041H19.59");
}

</style>
