<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdvpgmswv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cat-wand" /></template>
<style>
.fdvpgmswv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.983 2.343q.441 2.055.127 3.691q1.667-.334 3.606.248q.07.021.136.055q.065.035.122.082q.057.046.104.103t.082.122t.057.136t.029.144t.001.147q-.007.074-.029.145q-.008.027-.018.053q-1.066 2.771-3.319 3.705q-2.102.872-4.7-.094L3.53 21.53q-.105.106-.243.163T3 21.75t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 21t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113L13.121 9.818q-.958-2.611.039-4.815q1.067-2.358 3.869-3.22q.071-.022.145-.029q.073-.008.147-.001q.073.007.144.028t.136.056t.122.081q.058.047.105.104t.082.122t.057.135z");
}

</style>
