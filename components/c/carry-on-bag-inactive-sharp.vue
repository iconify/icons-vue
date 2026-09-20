<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxaqerb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:carry-on-bag-inactive-sharp" /></template>
<style>
.cxaqerb3o {
  fill: currentColor;
  d: path("m18.262 21.523l-3.174-3.098q.2.2.326.475t.124.6q0 .641-.449 1.09q-.45.449-1.091.449t-1.09-.45t-.447-1.091t.45-1.09T14 17.963q.28 0 .547.097q.266.097.466.291L13.77 17.1q-.942.083-1.567.765t-.625 1.635q0 .134.009.25t.05.25H9.386v-7.342l-.885-.885V20H6V9.262L1.939 5.2l.707-.708L18.97 20.816zM14 12.996L8.985 8H13V4h-1.616V3H14z");
}

</style>
