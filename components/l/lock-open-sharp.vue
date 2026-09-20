<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oueuxbq1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lock-open-sharp" /></template>
<style>
.oueuxbq1z {
  fill: currentColor;
  d: path("M5 21V9h10V7q0-1.25-.875-2.125T12 4t-2.125.875T9 7H8q0-1.671 1.165-2.835Q10.329 3 12 3t2.836 1.165T16 7v2h3v12zm8.066-4.934q.434-.433.434-1.066t-.434-1.066T12 13.5t-1.066.434Q10.5 14.367 10.5 15t.434 1.066q.433.434 1.066.434t1.066-.434");
}

</style>
