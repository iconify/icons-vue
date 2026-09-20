<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lbc4zhs6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:globe-x-fill" /></template>
<style>
.lbc4zhs6n {
  fill: currentColor;
  d: path("M128 24a104 104 0 0 0 0 208a8 8 0 0 0 5-14.21c-1.12-.91-20.88-17.32-31.06-49.77h26a8 8 0 0 0 0-16H98.08a140.2 140.2 0 0 1 0-48h59.88A138 138 0 0 1 160 128a8 8 0 0 0 16 0a155 155 0 0 0-1.84-24h38.51a87.6 87.6 0 0 1 3.33 24a8 8 0 0 0 16 0A104.11 104.11 0 0 0 128 24m-26 64a115.1 115.1 0 0 1 26-45a115.3 115.3 0 0 1 26 45Zm68.75 0a135.3 135.3 0 0 0-22.3-45.6a88.29 88.29 0 0 1 58 45.6Zm50.95 85.66L203.31 192l18.35 18.34a8 8 0 0 1-11.32 11.32L192 203.31l-18.34 18.35a8 8 0 0 1-11.32-11.32L180.69 192l-18.35-18.34a8 8 0 0 1 11.32-11.32L192 180.69l18.34-18.35a8 8 0 0 1 11.32 11.32Z");
}

</style>
