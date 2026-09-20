<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytbcq4b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-home-work-sharp" /></template>
<style>
.ytbcq4b3z {
  fill: currentColor;
  d: path("M17 9h2V7h-2zm1 14q-2.075 0-3.537-1.463T13 18t1.463-3.537T18 13t3.538 1.463T23 18t-1.463 3.538T18 23m-.5-2h1v-2.5H21v-1h-2.5V15h-1v2.5H15v1h2.5zm5.5-7.875q-.975-1.05-2.275-1.588T18 11q-.275 0-.513.013t-.487.062V10l-7-5.05V3h13zM1 21V11l7-5l7 5v.675q-1.8.85-2.9 2.588T11 18q0 .775.163 1.538T11.675 21H10v-6H6v6z");
}

</style>
