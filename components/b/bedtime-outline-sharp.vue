<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7bberbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bedtime-outline-sharp" /></template>
<style>
.v7bberbjj {
  fill: currentColor;
  d: path("M12.1 22q-2.1 0-3.937-.8t-3.2-2.162t-2.163-3.2T2 11.9q0-3.65 2.325-6.437T10.25 2q-.45 2.475.275 4.838t2.5 4.137t4.138 2.5T22 13.75q-.65 3.6-3.45 5.925T12.1 22m0-2q2.2 0 4.075-1.1t2.95-3.025q-2.15-.2-4.075-1.088t-3.45-2.412t-2.425-3.45T8.1 4.85Q6.175 5.925 5.088 7.813T4 11.9q0 3.375 2.363 5.738T12.1 20m-.5-7.625");
}

</style>
