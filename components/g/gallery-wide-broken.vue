<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bi127sxje"/><path class="wk1_5xrpd"/><circle class="t5vsymb5k"/><path class="q3b3n4bkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-wide-broken" /></template>
<style>
.bi127sxje {
  d: path("M22 14C22 17.7712 22 19.6569 20.8284 20.8284C19.6569 22 17.7712 22 14 22H10C6.22876 22 4.34315 22 3.17157 20.8284C2 19.6569 2 17.7712 2 14C2 10.2288 2 8.34315 3.17157 7.17157C4.34315 6 6.22876 6 10 6H14C17.7712 6 19.6569 6 20.8284 7.17157C21.4843 7.82742 21.773 8.70704 21.9001 10.0159");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q3b3n4bkx {
  d: path("M21.0667 20.56L17.7764 17.5986C16.7368 16.6631 15.1888 16.5702 14.0446 17.3744L13.7464 17.5839C12.9512 18.1428 11.8694 18.0491 11.1822 17.3618L6.89249 13.0721C6.03628 12.2159 4.66286 12.1702 3.75159 12.9675L2 14.5001");
}

.t5vsymb5k {
  cx: 17.5px;
  cy: 10.5px;
  r: 1.5px;
}

.wk1_5xrpd {
  d: path("M19.8377 6.51084V6C19.7253 5.06898 19.4906 4.42559 19.0005 3.93726C18.06 3 16.5462 3 13.5186 3H10.3074C7.2798 3 5.76602 3 4.82547 3.93726C4.33543 4.42559 4.10071 5.06898 3.98828 6L3.99545 6.58732");
}

</style>
