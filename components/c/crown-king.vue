<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3k_hubcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crown-king" /></template>
<style>
.q3k_hubcb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 4.75q0-2.5 2.5-2.5q1.036 0 1.768.732T14.5 4.75t-.732 1.768T12 7.25q-2.5 0-2.5-2.5m-2.088 7.212l-1.41-1.269l-.001-.001q-1.01-.906-2.193-.245t-.944 1.996l1.174 6.459q.336 1.848 2.214 1.848h11.496q1.878 0 2.214-1.848l1.174-6.46q.24-1.334-.944-1.995t-2.194.246l-1.409 1.268q-.546.49-1.048-.043l-1.903-2.021q-.666-.708-1.638-.708t-1.638.708l-1.903 2.021q-.502.533-1.047.044");
}

</style>
