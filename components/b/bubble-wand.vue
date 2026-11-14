<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2t0c1bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bubble-wand" /></template>
<style>
.u2t0c1bzc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 5q0-2.75 2.75-2.75T9.25 5T6.5 7.75T3.75 5m6 4.5q0-1.968 1.391-3.359T14.5 4.75t3.359 1.391T19.25 9.5t-1.391 3.359T14.5 14.25q-1.581 0-2.791-.899L4.53 20.53q-.105.106-.243.163T4 20.75t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.25 20t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l7.179-7.179Q9.75 11.081 9.75 9.5M19 14.75q-2.75 0-2.75 2.75T19 20.25t2.75-2.75T19 14.75m-8.25 4.75q0-2.25 2.25-2.25t2.25 2.25T13 21.75t-2.25-2.25");
}

</style>
