<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_w_qis0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lock-clock-outline-sharp" /></template>
<style>
.j_w_qis0u {
  fill: currentColor;
  d: path("M9 8h6V6q0-1.25-.875-2.125T12 3t-2.125.875T9 6zm3.25 14H4V8h3V6q0-2.075 1.463-3.537T12 1t3.538 1.463T17 6v2h3v3.3q-.45-.15-.937-.225T18 11v-1H6v10h5.3q.2.6.4 1.038t.55.962m2.213-.462Q13 20.075 13 18t1.463-3.537T18 13t3.538 1.463T23 18t-1.463 3.538T18 23t-3.537-1.463m5.187-1.187l.7-.7l-1.85-1.85V15h-1v3.2zM6 10v10z");
}

</style>
