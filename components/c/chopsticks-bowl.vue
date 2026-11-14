<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9al8-b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chopsticks-bowl" /></template>
<style>
.v9al8-b8x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.689 11.25h-2.141l6.541-8.285q.045-.058.079-.124t.054-.137t.026-.145t-.003-.147t-.032-.143q-.022-.071-.058-.135t-.084-.121t-.106-.102t-.124-.079t-.137-.054t-.145-.026q-.073-.005-.147.003q-.073.009-.143.032q-.071.022-.135.058t-.121.084t-.102.106L8.637 11.25H2.5q-.149 0-.287.057t-.243.163t-.163.243q-.057.138-.057.287q0 3.663 3.049 6.231Q7.791 20.75 12 20.75t7.201-2.519Q22.25 15.663 22.25 12q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-6.689l6.719-6.72q.106-.105.163-.243T21.75 4t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 3.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094z");
}

</style>
