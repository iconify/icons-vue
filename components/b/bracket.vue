<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omfnnhbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bracket" /></template>
<style>
.omfnnhbcj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.4 4.05q1.741-2.321 6.076-.85l.024.008l.024-.008q4.335-1.471 6.076.85q2.209 2.946.096 8.229q-.17.453-.345 1.283q-2.851.418-2.851 3.688v2.5q0 .485.107.926q-.244-.003-.519-.076q-1.299-.347-1.575-1.959l-.743-3.468Q10.721 15 10.5 15t-.27.173l-.743 3.468q-.276 1.612-1.575 1.959q-1.527.407-2.119-1.35q-.4-1.076-.785-3.639q-.363-2.422-.71-3.348Q2.191 6.996 4.4 4.05m12.85 10.7h2.5q1.036 0 1.768.732t.732 1.768v2.5q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732t-.732-1.768v-2.5q0-2.5 2.5-2.5m0 1.5q-1 0-1 1v2.5q0 .414.293.707t.707.293h2.5q.414 0 .707-.293t.293-.707v-2.5q0-1-1-1z");
}

</style>
