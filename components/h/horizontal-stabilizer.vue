<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwc6pkbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:horizontal-stabilizer" /></template>
<style>
.wwc6pkbdb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.956 4.941q-1.201-.353-2.204.397q-1.002.75-1.002 2.002v7.411q0-.069.012-.136t.037-.131t.06-.122t.081-.11q.045-.051.099-.093t.114-.073q.061-.032.126-.052q.066-.02.133-.028l17-2q.074-.008.147-.003q.074.006.145.026t.137.054t.124.079t.106.102t.084.121t.058.135t.032.143q.005.043.005.087v-1.44q-.001-1.87-1.794-2.398zm15.294 7.81q0 .126-.042.245q-.041.12-.119.219q-.093.117-.223.19q-.13.072-.278.09l-17 2q-.149.017-.292-.023q-.144-.041-.261-.133q-.117-.093-.19-.223q-.072-.13-.09-.278q-.005-.044-.005-.088v2.103q0 1.188.921 1.938q.92.75 2.083.511l13.5-2.779q1.996-.411 1.996-2.449z");
}

</style>
