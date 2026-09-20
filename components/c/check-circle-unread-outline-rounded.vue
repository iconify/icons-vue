<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy1-8zblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:check-circle-unread-outline-rounded" /></template>
<style>
.wy1-8zblv {
  fill: currentColor;
  d: path("M16.73 7.272Q16 6.543 16 5.502t.729-1.771T18.498 3t1.771.729T21 5.498t-.728 1.771t-1.77.731t-1.771-.728m-8.238 13.02q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51q.709-1.643 1.924-2.859T8.49 3.709T12 3q.523 0 1.046.072q.524.072 1.018.18q.188.056.28.236t.015.358q-.076.19-.265.292q-.19.103-.403.053q-.41-.108-.836-.15T12 4Q8.65 4 6.325 6.325T4 12t2.325 5.675T12 20t5.675-2.325T20 12q0-.429-.041-.855q-.042-.426-.15-.835q-.05-.21.052-.394t.29-.258t.365.008q.176.082.232.27q.108.494.18 1.018Q21 11.477 21 12q0 1.868-.708 3.51t-1.924 2.858t-2.856 1.923t-3.509.709t-3.51-.708m2.069-5.811l-2.496-2.49q-.141-.141-.342-.15t-.37.16q-.156.155-.156.349t.16.354l2.633 2.638q.242.242.565.242t.565-.242l5.206-5.206q.177-.176.146-.362t-.171-.326t-.326-.168t-.362.149z");
}

</style>
