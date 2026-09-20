<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_v3b-biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-charging-60-outline-sharp" /></template>
<style>
.n_v3b-biy {
  fill: currentColor;
  d: path("M7 22V4h3V2h4v2h3v8q-2.5.025-4.25 1.763T11 18q0 1.15.4 2.175T12.525 22zm2-10h6V6H9zm7.5 10v-3H14l3.5-5v3H20z");
}

</style>
