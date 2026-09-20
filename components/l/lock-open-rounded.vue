<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss2w-bblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lock-open-rounded" /></template>
<style>
.ss2w-bblw {
  fill: currentColor;
  d: path("M6.616 21q-.667 0-1.141-.475T5 19.386v-8.77q0-.666.475-1.14T6.615 9H15V7q0-1.25-.875-2.125T12 4q-1.12 0-1.959.734q-.839.733-.999 1.818q-.047.202-.193.325T8.507 7q-.22 0-.364-.15t-.107-.352q.16-1.489 1.288-2.493Q10.452 3 12 3q1.671 0 2.836 1.165Q16 5.329 16 7v2h1.385q.666 0 1.14.475t.475 1.14v8.77q0 .666-.475 1.14t-1.14.475zm6.45-4.934q.434-.433.434-1.066t-.434-1.066T12 13.5t-1.066.434Q10.5 14.367 10.5 15t.434 1.066q.433.434 1.066.434t1.066-.434");
}

</style>
