<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7q51mbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bronze-mirror" /></template>
<style>
.u7q51mbww {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 9.5q0-3.21 2.27-5.48T12 1.75t5.48 2.27t2.27 5.48t-2.27 5.48q-2 2-4.73 2.238V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-4.282q-2.73-.238-4.73-2.238q-2.27-2.27-2.27-5.48m5.25 0Q9.5 7 12 7q1.036 0 1.768.732T14.5 9.5t-.732 1.768T12 12q-2.5 0-2.5-2.5");
}

</style>
