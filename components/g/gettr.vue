<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e9dfw-bsc"/><path class="z6962hbax"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gettr" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e9dfw-bsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 25.467H13.539v.82s5.106.317 5.64 3.88H24m-1.842 15.254l-.738-8.074l-1-.736l-.897-4.303");
}

.z6962hbax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.154 35.232H24v-2.925m-1.909 2.925l-.388-2.924m4.139 13.113l.739-8.074l.999-.736l.897-4.303m-.631 2.924H24m1.909 0l.388-2.924M24 25.467h10.461v.82s-5.106.317-5.64 3.88H24m-.19-7.107s-4.354-5.202 0-8.785s8.922-2.709 11.676-5.194c0 0-.726 3.208-2.505 4.352c0 0 1.582.076 2.021-.584c0 0-1.432 2.973-2.774 3.62a4 4 0 0 0 1.723-.34s-.92 3.77-4.099 4.165s-6.042.575-6.042 2.766");
}

</style>
