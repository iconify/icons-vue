<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojdm7zbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-retrolux-outline-sharp" /></template>
<style>
.ojdm7zbpi {
  fill: currentColor;
  d: path("m14.666 20.066l-2.212-2.224q-.06 1.05-.841 1.797t-1.844.746q-1.148 0-1.94-.792q-.79-.791-.79-1.94q0-1.147.79-1.938q.792-.792 1.94-.792q.465 0 .883.146q.417.147.775.45L7 8.885l5-5.039l5 5.039l-4.461 6.692v.935l2.834 2.834zm-3.67-1.186q.504-.505.504-1.226t-.505-1.226q-.504-.505-1.226-.505t-1.226.505t-.504 1.226t.504 1.226t1.226.504t1.226-.504M12 14.592l3.72-5.611L12 5.26L8.28 8.98zm0-4.665");
}

</style>
