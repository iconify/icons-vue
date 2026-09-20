<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fa2n_sm6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-right-left-48-filled" /></template>
<style>
.fa2n_sm6b {
  fill: currentColor;
  d: path("M8.944 9.894a1.5 1.5 0 0 1 1.112-2.787L41.61 19.702c2.078.83 2.104 3.76.042 4.627L12.393 36.622l7.728 3.513a1.5 1.5 0 0 1-1.241 2.73l-11-5a1.5 1.5 0 0 1-.764-1.942l5-12a1.5 1.5 0 0 1 2.769 1.154l-3.659 8.781l28.137-11.822z");
}

</style>
