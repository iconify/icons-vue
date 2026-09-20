<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsu0unbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gal" /></template>
<style>
.zsu0unbrj {
  fill: var(--svg-color--fff, #fff);
  d: path("M3 21L20.238 6.646a2.05 2.05 0 1 0-2.884-2.884zm8.318-15.29l-7.26 5.447l5.446-7.26a1.294 1.294 0 1 1 1.814 1.813m8.785 8.786l-7.26 5.447l5.447-7.26a1.294 1.294 0 1 1 1.813 1.813");
}

</style>
