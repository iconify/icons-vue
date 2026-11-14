<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prakp5isv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:agent-data" /></template>
<style>
.prakp5isv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7M13 16.75q0-2.02 1.088-2.952q-1.607-.548-3.588-.548q-3.462 0-5.782 1.673Q2.25 16.702 2.25 19.5q0 1.75 1.75 1.75h9.3q-.3-.688-.3-1.5zm1.25 0q0-2.5 2.5-2.5h3q1.036 0 1.768.732t.732 1.768v3q0 1.036-.732 1.768t-1.768.732h-3q-1.036 0-1.768-.732t-.732-1.768zm3.25-1v1.75h-1.75v-.75q0-1 1-1zm3.25 1q0-1-1-1H19v1.75h1.75zM17.5 19h-1.75v.75q0 .414.293.707t.707.293h.75zm3.25 0H19v1.75h.75q.414 0 .707-.293t.293-.707z");
}

</style>
