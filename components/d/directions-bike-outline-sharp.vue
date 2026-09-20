<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlh21ac0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:directions-bike-outline-sharp" /></template>
<style>
.mlh21ac0i {
  fill: currentColor;
  d: path("M15.116 5.385q-.633 0-1.067-.434t-.433-1.066t.433-1.067t1.067-.433t1.066.433t.434 1.067t-.434 1.066t-1.066.434m-4.893 5l2.277 2.377V18.5h-1v-4.942l-4.642-3.523l4.088-4.089q.229-.229.524-.347t.63-.118t.63.118t.524.347l1.9 1.9q.656.656 1.527 1.088t1.919.527V10.5q-1.325-.096-2.37-.601t-1.884-1.345L13.2 7.408zm-4.838 2.23q1.856 0 3.12 1.265T9.769 17t-1.264 3.12t-3.12 1.264t-3.12-1.264T1 17t1.265-3.12t3.12-1.265m2.481 6.867Q8.885 18.463 8.885 17t-1.019-2.482T5.385 13.5t-2.482 1.018Q1.885 15.537 1.885 17t1.018 2.482T5.385 20.5q1.463 0 2.481-1.018m13.87-5.602Q23 15.144 23 17t-1.264 3.12t-3.12 1.264t-3.12-1.264T14.23 17t1.264-3.12q1.265-1.265 3.12-1.265t3.12 1.265m-.638 5.602q1.019-1.019 1.019-2.482t-1.019-2.482t-2.482-1.018t-2.481 1.018T15.116 17t1.018 2.482t2.482 1.018t2.481-1.018");
}

</style>
