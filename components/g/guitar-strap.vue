<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvpu8cbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:guitar-strap" /></template>
<style>
.pvpu8cbha {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.433 12.625q.412-1.888-.656-3.342L21.03 4.03q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094l-2.867 2.867Q11.334 3.012 6.964 4.378Q2.705 5.709 2.013 9.862q-.681 3.63.199 6.985q.476 1.816 1.37 2.449q1.069.757 2.237-.113Q7.189 20.25 9 20.25q2.175 0 3.712-1.538q1.357-1.356 1.517-3.209q1.765-.864 2.204-2.878m-1.716-4.402q-1.454-1.068-3.342-.656q-2.014.439-2.878 2.204q-1.853.16-3.209 1.517Q3.75 12.825 3.75 15q0 1.745.991 3.081q-.177.072-.292-.009q-.448-.318-.786-1.606q-.794-3.029-.176-6.328q.546-3.273 3.924-4.328q3.631-1.135 8.566 1.152zM6.75 15q0-2.25 2.25-2.25T11.25 15T9 17.25T6.75 15");
}

</style>
