<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="euo2u3bkq"/><path class="k66tt2kvs"/><path class="avzbbbb-w"/><circle class="enjp2ob5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-wide-line-duotone" /></template>
<style>
.avzbbbb-w {
  d: path("M19.8377 6.51084V6C19.7253 5.06898 19.4906 4.42559 19.0005 3.93726C18.06 3 16.5462 3 13.5186 3H10.3074C7.2798 3 5.76602 3 4.82547 3.93726C4.33543 4.42559 4.10071 5.06898 3.98828 6L3.99545 6.58732");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.enjp2ob5n {
  cx: 17.5px;
  cy: 10.5px;
  r: 1.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.euo2u3bkq {
  d: path("M21.0667 20.56L17.7764 17.5986C16.7368 16.6631 15.1888 16.5702 14.0446 17.3744L13.7464 17.5839C12.9512 18.1428 11.8694 18.0491 11.1822 17.3618L6.89249 13.0721C6.03628 12.2159 4.66286 12.1702 3.75159 12.9675L2 14.5001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k66tt2kvs {
  d: path("M10 22H14C17.7712 22 19.6569 22 20.8284 20.8284C22 19.6569 22 17.7712 22 14C22 10.2288 22 8.34315 20.8284 7.17157C19.6569 6 17.7712 6 14 6H10C6.22876 6 4.34315 6 3.17157 7.17157C2 8.34315 2 10.2288 2 14C2 17.7712 2 19.6569 3.17157 20.8284C4.34315 22 6.22876 22 10 22Z");
}

</style>
