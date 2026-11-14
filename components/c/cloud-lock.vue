<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-6o7abfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-lock" /></template>
<style>
.d-6o7abfq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 19.25q-1.968 0-3.359-1.391T2.25 14.5t1.391-3.359q1.152-1.152 2.7-1.35q.4-2.157 2.143-3.61q1.996-1.663 4.584-1.428t4.251 2.231q1.446 1.736 1.457 3.919q1.298.388 2.152 1.526q1.064 1.42.813 3.177t-1.67 2.822q-1.398 1.048-3.122.822zm4.25-7h1.5V12q0-.75-.75-.75t-.75.75zm3 .214V12q0-2.25-2.25-2.25T9.75 12v.464q-1.25.518-1.25 2.286v.5q0 2.5 2.5 2.5h2q2.5 0 2.5-2.5v-.5q0-1.768-1.25-2.286");
}

</style>
