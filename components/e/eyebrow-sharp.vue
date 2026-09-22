<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2l0v9box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:eyebrow-sharp" /></template>
<style>
.d2l0v9box {
  fill: currentColor;
  d: path("M15 14q-.775 0-1.937.238t-2.726.725T6.8 16.175T2.375 17.9L1 16.975V8.95q3.45-.675 6.963-1.312T15 7q3.1 0 5.313 2.488T23.025 16l-1.775.675q-1.6-1.25-3.275-1.963T15 14");
}

</style>
