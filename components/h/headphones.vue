<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trqyubbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:headphones" /></template>
<style>
.trqyubbdn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 12.989V12.5q0-3.21 2.27-5.48T12 4.75t5.48 2.27t2.27 5.48v.489q.573.238 1.048.713q.952.952.952 2.298v2q0 1.346-.952 2.298t-2.298.952q-3.25 0-3.25-3.25v-2q0-3.122 3-3.245V12.5q0-2.589-1.831-4.419Q14.589 6.25 12 6.25T7.581 8.081Q5.75 9.911 5.75 12.5v.255q3 .123 3 3.245v2q0 3.25-3.25 3.25T2.25 18v-2q0-1.346.952-2.298q.475-.475 1.048-.713");
}

</style>
