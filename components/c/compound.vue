<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezcl6w1as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:compound" /></template>
<style>
.ezcl6w1as {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 9.5q0-2.175 1.538-3.712Q9.825 4.25 12 4.25t3.712 1.538Q17.25 7.325 17.25 9.5q0 1.719-.961 3.04l.938 1.055q.714-.345 1.773-.345q3.25 0 3.25 3.25T19 19.75t-3.25-3.25q0-1.13.393-1.867l-.893-1.004Q13.857 14.75 12 14.75t-3.25-1.121l-.893 1.004q.393.737.393 1.867q0 3.25-3.25 3.25T1.75 16.5T5 13.25q1.059 0 1.773.345l.938-1.055Q6.75 11.219 6.75 9.5");
}

</style>
