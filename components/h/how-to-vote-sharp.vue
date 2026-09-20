<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwo-lbclm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:how-to-vote-sharp" /></template>
<style>
.qwo-lbclm {
  fill: currentColor;
  d: path("M3 22v-6.55l2.75-3.125l1.425 1.425l-2 2.25h13.65l-1.95-2.2l1.425-1.425L21 15.45V22zm9.025-6.175L5.7 9.45l7.75-7.75l6.375 6.325zm.025-2.875L17 8l-3.55-3.5L8.5 9.45z");
}

</style>
