<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyz0xdgqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:emergency-exit-warehouse" /></template>
<style>
.eyz0xdgqr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 2.75h9q1.76 0 3.005 1.245T20.75 7v10q0 1.76-1.245 3.005T16.5 21.25h-9q-1.76 0-3.005-1.245T3.25 17V7q0-1.76 1.245-3.005T7.5 2.75m2.5 3Q7.75 5.75 7.75 8T10 10.25T12.25 8T10 5.75m-.671 4.915l-3 6q-.033.066-.052.137q-.02.071-.025.145t.004.147t.032.143q.024.07.06.134q.037.065.085.12q.049.056.107.101q.059.046.125.079q.133.067.282.077q.149.011.29-.036q.142-.048.254-.145q.113-.098.18-.232l2.534-5.069l2.265 2.264q.105.106.243.163t.287.057h3q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 13.25h-2.689l-2.781-2.78q-.086-.086-.195-.141q-.066-.033-.137-.052q-.071-.02-.145-.025t-.147.004t-.143.032t-.134.06t-.12.085t-.101.107t-.079.125");
}

</style>
