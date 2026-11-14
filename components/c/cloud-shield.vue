<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmcf6accx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-shield" /></template>
<style>
.pmcf6accx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.788 18.212Q4.325 19.75 6.5 19.75h11q1.968 0 3.359-1.391T22.25 15t-1.391-3.359q-1.109-1.109-2.584-1.334q-.042-2.125-1.456-3.823q-1.664-1.996-4.251-2.231T7.984 5.681Q6.243 7.132 5.842 9.287q-1.755.201-3.054 1.501Q1.25 12.325 1.25 14.5t1.538 3.712m9.5-9.404l3 1.25q.103.042.189.113q.085.071.147.163t.094.199t.032.217v2q0 2.959-3.544 3.971q-.206.059-.412 0Q8.25 15.709 8.25 12.75v-2q0-.111.032-.217q.032-.107.094-.199t.147-.163t.189-.113l3-1.25q.138-.058.288-.058t.288.058");
}

</style>
