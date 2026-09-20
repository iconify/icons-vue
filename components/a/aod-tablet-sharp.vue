<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a60dc9bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:aod-tablet-sharp" /></template>
<style>
.a60dc9bnn {
  fill: currentColor;
  d: path("M1 20V4h22v16zm5-2h12V6H6zm2-6.5V10h8v1.5zm1 3V13h6v1.5z");
}

</style>
