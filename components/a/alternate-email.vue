<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2bxq6b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:alternate-email" /></template>
<style>
.p2bxq6b2c {
  fill: currentColor;
  d: path("M12 21q-1.864 0-3.506-.71q-1.642-.711-2.857-1.926q-1.216-1.216-1.926-2.858Q3 13.864 3 12t.71-3.506t1.927-2.857T8.494 3.71Q10.137 3 12 3t3.506.71q1.642.711 2.857 1.927q1.216 1.215 1.926 2.857Q21 10.137 21 12v.989q0 1.263-.868 2.137T18 16q-.894 0-1.63-.49q-.737-.49-1.09-1.306q-.57.821-1.425 1.308T12 16q-1.671 0-2.835-1.164Q8 13.67 8 12t1.165-2.835T12 8t2.836 1.165T16 12v.989q0 .822.589 1.417T18 15t1.412-.594t.588-1.418V12q0-3.35-2.325-5.675T12 4T6.325 6.325T4 12t2.325 5.675T12 20h5v1zm2.125-6.875Q15 13.25 15 12t-.875-2.125T12 9t-2.125.875T9 12t.875 2.125T12 15t2.125-.875");
}

</style>
