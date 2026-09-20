<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8sj99-1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-tab-rounded" /></template>
<style>
.w8sj99-1j {
  fill: currentColor;
  d: path("M20.143 17.357Q20 17.214 20 17V7q0-.213.143-.357T20.5 6.5t.357.143T21 7v10q0 .214-.143.357t-.357.143t-.357-.143m-4.43-4.857H3.5q-.213 0-.357-.143T3 12t.143-.357t.357-.143h12.194l-3.721-3.765q-.14-.14-.133-.332q.006-.191.152-.337q.14-.141.344-.141q.205 0 .345.14l4.369 4.37q.13.13.184.267q.052.137.052.298t-.052.298t-.184.268l-4.389 4.388q-.14.14-.34.14t-.348-.14q-.165-.146-.156-.357q.01-.21.156-.357z");
}

</style>
