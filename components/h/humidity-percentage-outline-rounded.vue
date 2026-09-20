<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f21ro9b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:humidity-percentage-outline-rounded" /></template>
<style>
.f21ro9b6j {
  fill: currentColor;
  d: path("M14.822 16.825q.294-.292.294-.707q0-.416-.291-.71q-.292-.292-.707-.292q-.416 0-.71.29t-.292.707t.29.709t.707.294t.709-.291m-5.375.206q.204 0 .357-.146l5.08-5.081q.147-.153.147-.357t-.146-.35t-.347-.147t-.347.146l-5.095 5.095q-.146.146-.146.347t.146.347t.35.146m1.145-4.437q.294-.291.294-.707t-.291-.709t-.707-.294t-.709.292q-.293.29-.293.706t.29.71t.707.293q.416 0 .71-.291m-3.593 6.344Q5 16.875 5 13.803q0-1.36.62-2.74q.619-1.38 1.547-2.648q.93-1.269 2.006-2.392q1.077-1.124 2-1.956q.18-.161.393-.249q.212-.087.434-.087t.434.087t.393.25q.923.83 2 1.955q1.077 1.123 2.006 2.391t1.548 2.649t.619 2.74q0 3.072-2.002 5.135Q14.994 21 11.996 21t-4.998-2.062m9.301-.7Q18 16.475 18 13.8q0-1.825-1.513-4.125T12 4.65Q9.025 7.375 7.513 9.675T6 13.8q0 2.675 1.7 4.438T12 20t4.3-1.763M12 12.155");
}

</style>
