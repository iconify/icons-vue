<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7lbw2bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caret-left" /></template>
<style>
.m7lbw2bbe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.174 10.351l3.295-3.06q1.079-1.003 2.43-.414T15.25 8.94v6.12q0 1.474-1.351 2.063t-2.43-.415l-3.295-3.059q-.719-.668-.719-1.649t.719-1.649");
}

</style>
