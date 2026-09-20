<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko1dyp1pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:energy-savings-leaf-sharp" /></template>
<style>
.ko1dyp1pe {
  fill: currentColor;
  d: path("m10.55 16.55l4.875-4.325l-.275-.8l-3.6-.35l2.325-3.25l-.4-.425L8.6 11.75l.275.8l3.6.35l-2.35 3.225zM12 20q-1.4 0-2.637-.437T7.1 18.325l-2.1 2.1L3.575 19l2.1-2.1q-.8-1.025-1.237-2.262T4 12q0-3.35 2.325-5.675T12 4h8v8q0 3.35-2.325 5.675T12 20");
}

</style>
