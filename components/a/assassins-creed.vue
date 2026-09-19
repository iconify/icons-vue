<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yq-n6_l3x"/><path class="u_tat56gq"/><path class="vi_llzzjy"/><path class="q_f4dcb9v"/><path class="k051tub_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:assassins-creed" /></template>
<style>
.k051tub_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.321 43.196C29.913 43.751 24 44.5 24 41.975c0 2.525-5.913 1.776-7.321 1.221");
}

.q_f4dcb9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.857 36.246C35.497 42.16 30.16 44.5 24 44.5s-11.498-2.34-16.857-8.254");
}

.u_tat56gq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.588 40.622c6.515-1.916 10.02-5.366 8.924-8.377S24 3.5 24 3.5s-9.417 25.734-10.512 28.745s2.409 6.46 8.924 8.377");
}

.vi_llzzjy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.117 22.952c.487 1.331 3.875 6.555 8.747 4.2c-1.957 4.025.233 7.119.233 7.119c-2.033-.561-3.71.797-5.386 2.334c-1.39 1.273-3.251 2.1-7.698 3.557");
}

.yq-n6_l3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.883 22.952c-.487 1.331-3.875 6.555-8.747 4.2c1.957 4.025-.233 7.119-.233 7.119c2.033-.561 3.71.797 5.386 2.334c1.39 1.273 3.251 2.1 7.698 3.557");
}

</style>
