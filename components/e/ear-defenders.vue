<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbqhfdbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ear-defenders" /></template>
<style>
.lbqhfdbym {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 9.814V9.5q.001-2.899 2.051-4.948T12 2.502t4.949 2.05Q18.999 6.601 19 9.5v.314q1.181.211 2.078 1.108q1.172 1.171 1.172 2.828v3.5q0 1.657-1.172 2.828q-1.171 1.172-2.828 1.172q-4 0-4-4v-3.5q0-3.606 3.25-3.961V9.5q-.001-2.277-1.612-3.888q-1.61-1.61-3.888-1.61t-3.888 1.61Q6.501 7.223 6.5 9.5v.289q3.25.355 3.25 3.961v3.5q0 4-4 4t-4-4v-3.5q0-1.657 1.172-2.828q.897-.897 2.078-1.108");
}

</style>
