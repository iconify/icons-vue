<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h88hzqbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:android-outline-sharp" /></template>
<style>
.h88hzqbqb {
  fill: currentColor;
  d: path("M2.692 16.98q.212-2.22 1.35-4.044T6.98 9.975L5.36 7.269q-.186-.292-.093-.634q.093-.343.386-.523q.292-.187.634-.096q.343.09.523.382l1.673 2.806q.816-.342 1.7-.513q.883-.172 1.816-.172t1.816.172q.884.17 1.7.513l1.672-2.806q.181-.292.523-.382q.343-.091.635.096q.292.18.383.523q.09.342-.09.634L17.02 9.975q1.798 1.139 2.937 2.962t1.35 4.044zm14.388-3.19q.028-.361-.19-.728q-.217-.368-.56-.473t-.628.08t-.318.554q-.03.367.187.735q.217.367.563.466q.345.099.631-.088q.287-.186.315-.547m-9.21.622q.341-.105.559-.473q.217-.348.19-.718q-.029-.37-.315-.557q-.287-.186-.632-.087t-.563.466q-.217.348-.186.725q.03.377.317.564t.63.08");
}

</style>
