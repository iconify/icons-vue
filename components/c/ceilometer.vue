<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3m4b1ict"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ceilometer" /></template>
<style>
.z3m4b1ict {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.685 10.68q.15.07.315.07h8q3.5 0 3.5-3.5q0-3.282-3.077-3.486q-1.534-2.267-4.367-1.974q-2.816.292-3.858 2.795q-2.012.456-2.357 2.64q-.383 2.424 1.844 3.455m9.065 6.57h-4v-2.439l.97.969q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113l-2.25-2.25q-.105-.106-.243-.163T12 12.25h-.004q-.148.001-.285.058t-.241.162l-2.25 2.25q-.053.052-.094.113t-.069.13t-.043.141T9 15.25t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l.97-.969v2.439h-4q-2.5 0-2.5 2.5q0 1.036.732 1.768t1.768.732h9.5q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732");
}

</style>
