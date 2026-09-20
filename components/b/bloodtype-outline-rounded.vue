<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-u732bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bloodtype-outline-rounded" /></template>
<style>
.n-u732bdl {
  fill: currentColor;
  d: path("M6.999 18.938Q5 16.875 5 13.803q0-1.36.62-2.74q.619-1.38 1.547-2.648q.93-1.269 2.006-2.392q1.077-1.124 2-1.956q.18-.161.393-.249q.212-.087.434-.087t.434.087t.393.25q.923.83 2 1.955q1.077 1.123 2.006 2.391t1.548 2.649t.619 2.74q0 3.072-2.002 5.135Q14.994 21 11.996 21t-4.998-2.062m9.301-.7Q18 16.475 18 13.8q0-1.825-1.513-4.125T12 4.65Q9.025 7.375 7.513 9.675T6 13.8q0 2.675 1.7 4.438T12 20t4.3-1.763M10 17.5h4q.213 0 .356-.144t.144-.357t-.144-.356T14 16.5h-4q-.213 0-.356.144t-.144.357t.144.356t.356.143m1.5-5V14q0 .213.144.356t.357.144t.356-.144T12.5 14v-1.5H14q.213 0 .356-.144t.144-.357t-.144-.356T14 11.5h-1.5V10q0-.213-.144-.356t-.357-.144t-.356.144T11.5 10v1.5H10q-.213 0-.356.144t-.144.357t.144.356t.356.143z");
}

</style>
