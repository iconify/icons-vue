<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i99g-e1rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:carry-on-bag-sharp" /></template>
<style>
.i99g-e1rz {
  fill: currentColor;
  d: path("M13.909 20.589q-.447-.45-.447-1.091t.449-1.09q.45-.446 1.091-.446t1.09.449t.447 1.091t-.45 1.09q-.45.447-1.091.447t-1.09-.45M7 20V8h2.5v12zm3.385 0V8H14V4h-1.616V3H15v14.077q-1.01 0-1.716.707t-.707 1.716q0 .134.009.25t.05.25z");
}

</style>
