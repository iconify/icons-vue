<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkty97b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lock-open-right-rounded" /></template>
<style>
.kkty97b7m {
  fill: currentColor;
  d: path("M13.066 16.066q.434-.433.434-1.066t-.434-1.066T12 13.5t-1.066.434Q10.5 14.367 10.5 15t.434 1.066q.433.434 1.066.434t1.066-.434M6.616 21q-.667 0-1.141-.475T5 19.386v-8.77q0-.666.475-1.14T6.615 9H14V7q0-1.671 1.165-2.835Q16.329 3 18 3q1.567 0 2.686 1.03t1.278 2.516q.03.19-.109.322T21.501 7t-.355-.117q-.14-.118-.188-.325q-.16-1.085-.986-1.822Q19.146 4 18 4q-1.25 0-2.125.875T15 7v2h2.385q.666 0 1.14.475t.475 1.14v8.77q0 .666-.475 1.14t-1.14.475z");
}

</style>
