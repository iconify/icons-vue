<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea8quubkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dory" /></template>
<style>
.ea8quubkf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.505 7.25l2.151-3.887q.072-.13.089-.279q.017-.148-.024-.291q-.041-.144-.134-.26t-.224-.189q-.064-.036-.135-.058q-.07-.023-.144-.031t-.147-.002t-.144.026q-.071.021-.137.054q-.065.034-.123.08t-.106.103t-.083.121L12.79 7.25H3q-.113 0-.221.033q-.07.022-.135.057t-.122.082t-.104.105t-.081.122q-.034.065-.056.136t-.028.144q-.007.074.001.147q.007.074.029.145l2 6.5q.018.057.044.11q.027.054.061.103q.035.048.077.091t.089.078t.102.063t.109.046q.057.019.116.029q.059.009.119.009h3.362l-.468.844Q7.603 16 7.25 16q-2 0-2 3t2 3t2-3q0-1.089-.263-1.782l1.089-1.968H13.5q6.554 0 8.717-7.029q.033-.108.033-.221q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014z");
}

</style>
