<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhwkn5d1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:light-switch" /></template>
<style>
.dhwkn5d1u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.375 2.75h7.25q2.123 0 3.624 1.501t1.501 3.624v8.25q0 2.123-1.501 3.624t-3.624 1.501h-7.25q-2.123 0-3.624-1.501T3.25 16.125v-8.25q0-2.123 1.501-3.624T8.375 2.75m4 3h-.75q-3.375 0-3.375 3.375v5.75q0 3.375 3.375 3.375h.75q3.375 0 3.375-3.375v-5.75q0-3.375-3.375-3.375");
}

</style>
