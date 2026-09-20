<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpchl236o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:carry-on-bag-outline-sharp" /></template>
<style>
.jpchl236o {
  fill: currentColor;
  d: path("M15 17.077q1.01 0 1.716.707t.707 1.716t-.707 1.716t-1.716.707q-.873 0-1.53-.54T12.636 20H7V8h7V4h-1.616V3H15zM9.5 19V9H8v10zm1-10v10h2.156q.061-.586.43-1.024t.914-.63V9zm5.591 11.589q.448-.45.448-1.091t-.45-1.09q-.45-.446-1.091-.446t-1.09.449q-.446.45-.446 1.091t.449 1.09t1.091.447t1.09-.45M9.5 19V9zm1-10v10z");
}

</style>
