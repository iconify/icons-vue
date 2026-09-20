<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="febjpbbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lips-outline-rounded" /></template>
<style>
.febjpbbps {
  fill: currentColor;
  d: path("M11.967 12.539q2.506 0 4.815-.566q2.309-.565 3.709-.99l-3.864-3.556q-.208-.188-.472-.292t-.522-.104q-.17 0-.326.037t-.301.138L12.44 8.775q-.193.137-.429.137t-.428-.137L9.117 7.264q-.183-.12-.388-.176q-.205-.057-.393-.057q-.239 0-.465.085q-.226.084-.414.253l-3.954 3.633q1.356.425 3.658.98q2.302.557 4.807.557M11.677 17l.665.02q2.72 0 4.855-1.387t3.332-3.683q-1.27.43-3.602 1.01q-2.333.579-4.965.579q-2.537 0-4.828-.553t-3.6-.978q1.293 2.277 3.31 3.634T11.677 17m.665 1h-.665q-3.183 0-5.578-1.628t-3.71-4.387q-.2-.404-.102-.859t.436-.753l4-3.673q.348-.31.76-.485t.879-.176q.334 0 .656.095t.62.268l2.381 1.464L14.4 6.402q.298-.173.61-.268q.313-.096.648-.096q.465 0 .887.176t.77.486l3.962 3.673q.337.298.445.743q.109.446-.091.869q-1.194 2.76-3.708 4.387Q15.41 18 12.343 18");
}

</style>
