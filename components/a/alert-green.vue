<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilpgambrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:alert-green" /></template>
<style>
.ilpgambrb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.066 3.434Q14.382 1.75 12 1.75T7.934 3.434T6.25 7.5v9q0 2.382 1.684 4.066T12 22.25t4.066-1.684T17.75 16.5v-9q0-2.382-1.684-4.066M9.75 6.75Q9.75 4.5 12 4.5t2.25 2.25T12 9T9.75 6.75m2.25 3q2.25 0 2.25 2.25T12 14.25T9.75 12T12 9.75m-2.5 7.5q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768T12 19.75q-2.5 0-2.5-2.5");
}

</style>
