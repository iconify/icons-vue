<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8ned2b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-retrolux-sharp" /></template>
<style>
.b8ned2b8x {
  fill: currentColor;
  d: path("m14.666 20.066l-2.212-2.224q-.06 1.05-.841 1.797t-1.844.746q-1.148 0-1.94-.792q-.79-.791-.79-1.94q0-1.147.79-1.938q.792-.792 1.94-.792q.465 0 .883.146q.417.147.775.45L7 8.885l5-5.039l5 5.039l-4.461 6.692v.935l2.834 2.834zm-3.67-1.186q.504-.505.504-1.226t-.505-1.226q-.504-.505-1.226-.505t-1.226.505t-.504 1.226t.504 1.226t1.226.504t1.226-.504");
}

</style>
