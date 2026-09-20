<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuci_-n_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hardware-sharp" /></template>
<style>
.yuci_-n_f {
  fill: currentColor;
  d: path("M10.27 11.5V7H5.845q.289-1.325 1.357-2.162Q8.27 4 9.653 4h4.616v2.885L17.154 4h1v6.77h-1l-2.885-2.885V11.5zm0 8.5v-7.48h4V20z");
}

</style>
