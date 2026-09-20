<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjf-rx0yq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lock-open-right" /></template>
<style>
.kjf-rx0yq {
  fill: currentColor;
  d: path("M13.066 16.066q.434-.433.434-1.066t-.434-1.066T12 13.5t-1.066.434Q10.5 14.367 10.5 15t.434 1.066q.433.434 1.066.434t1.066-.434M6.616 21q-.667 0-1.141-.475T5 19.386v-8.77q0-.666.475-1.14T6.615 9H14V7q0-1.671 1.165-2.835Q16.329 3 18 3t2.836 1.165T22 7h-1q0-1.25-.875-2.125T18 4t-2.125.875T15 7v2h2.385q.666 0 1.14.475t.475 1.14v8.77q0 .666-.475 1.14t-1.14.475z");
}

</style>
