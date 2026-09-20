<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_1ehxbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lock-open" /></template>
<style>
.k_1ehxbtg {
  fill: currentColor;
  d: path("M6.616 9H15V7q0-1.25-.875-2.125T12 4t-2.125.875T9 7H8q0-1.671 1.165-2.835Q10.329 3 12 3t2.836 1.165T16 7v2h1.385q.666 0 1.14.475t.475 1.14v8.77q0 .666-.475 1.14t-1.14.475H6.615q-.666 0-1.14-.475T5 19.386v-8.77q0-.666.475-1.14T6.615 9m6.451 7.066q.434-.433.434-1.066t-.434-1.066T12 13.5t-1.066.434Q10.5 14.367 10.5 15t.434 1.066q.433.434 1.066.434t1.066-.434");
}

</style>
