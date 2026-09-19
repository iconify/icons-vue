<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t08gt3bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-temple-hindu" /></template>
<style>
.t08gt3bgv {
  fill: currentColor;
  d: path("M6.6 11h10.8l-.9-3h-9zM20 11v2H4v-2H2v11h8v-5h4v5h8V11zm-4.1-5L15 3V1h-2v2h-2.03V1h-2v2.12L8.1 6z");
}

</style>
