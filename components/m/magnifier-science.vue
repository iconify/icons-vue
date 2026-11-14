<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqr4dyb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:magnifier-science" /></template>
<style>
.cqr4dyb8i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 8.5q0-2.589 1.831-4.419Q8.411 2.25 11 2.25t4.419 1.831T17.25 8.5t-1.831 4.419T11 14.75q-2.206 0-3.861-1.329L3.53 17.03q-.105.106-.243.163T3 17.25t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l3.609-3.609Q4.75 10.706 4.75 8.5m9.5 9q0-3.25 3.25-3.25t3.25 3.25t-3.25 3.25t-3.25-3.25");
}

</style>
