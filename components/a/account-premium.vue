<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d165x5dwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:account-premium" /></template>
<style>
.d165x5dwb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.262 3.25h3.737q-.065 0-.129.011q-.147.026-.273.107q-.126.08-.211.202L8.11 8.25H3.013q.19-.705.759-1.417l1.854-2.317Q6.64 3.25 8.262 3.25m12.725 5H15.89l-3.276-4.68q-.075-.109-.184-.184q-.193-.136-.429-.136h3.737q1.622 0 2.636 1.266l1.854 2.317q.569.712.759 1.417M12 5.308l2.06 2.942H9.94zM7.959 9.75H3.038q.215.698.808 1.389l5.592 6.524q.64.748 1.499 1.021zm5.104 8.934q.859-.273 1.499-1.021l5.592-6.524q.593-.691.808-1.389h-4.921zm1.396-8.934H9.541L12 17.128z");
}

</style>
