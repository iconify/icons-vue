<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5dx1x55z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-retrolux-rounded" /></template>
<style>
.o5dx1x55z {
  fill: currentColor;
  d: path("m14.306 19.7l-1.852-1.858q-.06 1.05-.841 1.797t-1.844.746q-1.148 0-1.94-.792q-.79-.791-.79-1.94q0-1.147.79-1.938q.792-.792 1.94-.792q.465 0 .883.146q.417.147.775.45L7.373 9.425q-.161-.242-.143-.516q.018-.272.23-.484l3.975-3.994q.13-.131.267-.184T12 4.194t.298.053t.268.184l3.975 3.994q.211.212.23.485q.017.273-.144.515l-4.088 6.152v.935l2.48 2.48q.14.14.153.342q.013.2-.147.366q-.165.166-.36.166t-.36-.166m-3.31-.82q.505-.505.505-1.226t-.505-1.226t-1.226-.505t-1.226.505t-.504 1.226t.504 1.226t1.226.504t1.226-.504");
}

</style>
