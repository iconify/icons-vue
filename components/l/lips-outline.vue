<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s64ph306g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lips-outline" /></template>
<style>
.s64ph306g {
  fill: currentColor;
  d: path("m11.677 17l.665.02q2.72 0 4.855-1.387t3.332-3.683q-1.27.43-3.602 1.01q-2.333.579-4.965.579q-2.537 0-4.828-.553t-3.6-.978q1.293 2.277 3.31 3.634T11.677 17m0 1q-3.463 0-5.973-1.898T2 11.058L6.723 6.7q.348-.31.76-.486t.879-.176q.334 0 .656.096q.323.095.62.268l2.381 1.464L14.4 6.402q.298-.173.61-.268q.313-.096.648-.096q.465 0 .887.176t.77.486L22 11.039q-1.021 3.127-3.675 5.044T12.342 18zm.29-5.462q2.506 0 4.815-.565t3.709-.99l-3.864-3.556q-.208-.188-.472-.292t-.522-.104q-.17 0-.326.037t-.301.138l-2.987 1.828l-2.903-1.77q-.183-.12-.388-.177t-.393-.056q-.239 0-.465.084q-.226.085-.414.254l-3.954 3.633q1.356.425 3.658.98q2.302.557 4.807.557");
}

</style>
