<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj39ppbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dental-sealant" /></template>
<style>
.mj39ppbaw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.376 2.334q.083-.125.208-.208q.061-.041.13-.069q.068-.028.14-.043T12.001 2q.074 0 .146.015q.073.014.141.042t.129.07t.114.093q.052.053.093.114q.28.42.878 1.215Q15 5.541 15 6.5q0 3-3 3t-3-3q0-.959 1.498-2.951q.598-.795.878-1.215M12 11.511q1.467-1.089 3.634-.883q3.116.297 3.116 3.372q0 1.264-.711 2.93q-.394.923-.565 1.514l-.496 1.988q-.33 1.318-1.478 1.318q-1.125 0-1.464-1.266l-.982-2.455l-.016-.042q-.016-.049-1.038-.049t-1.038.049l-.016.042l-.982 2.455Q9.625 21.75 8.5 21.75q-1.148 0-1.478-1.318l-.496-1.988q-.171-.591-.565-1.514Q5.25 15.264 5.25 14q0-3.075 3.116-3.372q2.167-.206 3.634.883");
}

</style>
