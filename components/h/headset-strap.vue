<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omhd0mber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:headset-strap" /></template>
<style>
.omhd0mber {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.816 9.219Q4.673 8.75 6 8.75h12q1.327 0 2.184.469q-.455-.796-1.426-1.437Q16.251 6.125 12 6.125T5.242 7.782q-.971.641-1.426 1.437M21.75 12.63v2.87q0 3.75-3.75 3.75h-3q-.097 0-.191-.025q-.094-.024-.179-.072t-.154-.116t-.119-.151l-1.282-2.136h-2.15l-1.282 2.136q-.05.083-.119.151q-.07.068-.154.116q-.085.048-.179.072q-.094.025-.191.025H6q-3.75 0-3.75-3.75v-2.87Q.925 8.837 4.415 6.531Q7.298 4.625 12 4.625t7.585 1.906q3.49 2.306 2.165 6.099");
}

</style>
