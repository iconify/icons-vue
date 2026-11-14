<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_dth46ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hex-nut" /></template>
<style>
.k_dth46ob {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.781 4.925q-.847-1.468-2.543-1.469H8.763q-1.696.001-2.543 1.469l-3.239 5.606q-.848 1.469.001 2.938l3.237 5.606q.848 1.468 2.544 1.469h6.474q1.696-.001 2.543-1.469l3.239-5.606q.848-1.469-.001-2.938zM7.25 12q0-1.968 1.391-3.359T12 7.25t3.359 1.391T16.75 12t-1.391 3.359T12 16.75t-3.359-1.391T7.25 12");
}

</style>
