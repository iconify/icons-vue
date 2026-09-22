<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2a7c5bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:display-group-outline" /></template>
<style>
.i2a7c5bez {
  fill: currentColor;
  d: path("M4.827 6H4h16zM3 14.558V6.616q0-.667.475-1.141T4.615 5h14.77q.666 0 1.14.475T21 6.615v7.943h-1V6.616q0-.27-.173-.443T19.385 6H4.615q-.269 0-.442.173T4 6.616v7.942zM4 19q0-1.477 1.045-2.508t2.513-1.03q.195 0 .378.012t.378.062q-.83.68-1.335 1.563T6.288 19zm3.548-4.442q-.561 0-.958-.397q-.398-.397-.398-.959t.4-.959t.966-.397q.558 0 .952.4t.394.965q0 .558-.397.952t-.959.395M7.196 19q.331-1.667 1.669-2.786t3.13-1.118t3.125 1.119T16.785 19zM12 14.116q-.72 0-1.196-.477q-.477-.477-.477-1.187t.477-1.186t1.187-.478q.709 0 1.186.478t.477 1.176q0 .72-.478 1.196T12 14.117m4.423.442q-.557 0-.952-.397t-.394-.959t.397-.959t.959-.397q.561 0 .958.4q.398.4.398.965q0 .558-.4.952q-.4.395-.966.395M17.656 19q-.258-1.002-.782-1.871t-1.341-1.554q.238-.07.445-.091q.207-.022.445-.022q1.468 0 2.513 1.03T19.98 19z");
}

</style>
