<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni95kk5wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lock-clock-outline-sharp" /></template>
<style>
.ni95kk5wm {
  fill: currentColor;
  d: path("M9 9h6V7q0-1.25-.875-2.125T12 4t-2.125.875T9 7zm3.673 12H5V9h3V7q0-1.671 1.165-2.835Q10.329 3 12 3t2.836 1.165T16 7v2h3v2.8q-.2-.073-.457-.11q-.256-.036-.543-.036V10H6v10h6.146q.085.292.208.528t.319.472m2.107-.549q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164t1.165 2.836q0 1.67-1.165 2.835t-2.835 1.165q-1.672 0-2.836-1.165m4.486-.64l.546-.545L18 17.454V14.73h-.77v3.046zM6 15.77V20V10z");
}

</style>
