<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea1w9l6_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arm-track" /></template>
<style>
.ea1w9l6_e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.125 2.25h-2.25q-3.573 0-6.099 2.526T2.25 10.875v2.25q0 3.573 2.526 6.099t6.099 2.526h2.25q3.573 0 6.099-2.526t2.526-6.099v-2.25q0-3.573-2.526-6.099T13.125 2.25M6.75 12q0-2.175 1.538-3.712Q9.825 6.75 12 6.75t3.712 1.538Q17.25 9.825 17.25 12t-1.538 3.712Q14.175 17.25 12 17.25t-3.712-1.538Q6.75 14.175 6.75 12");
}

</style>
