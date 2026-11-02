<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqvk61b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-alt-fill" /></template>
<style>
.dqvk61b9j {
  fill: currentColor;
  d: path("M5 4h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3m4.943 11.787c.333.146.694.213 1.057.213a1 1 0 0 0 0-2c-.324 0-.5-.175-.5-.5s.176-.5.5-.5a1 1 0 0 0 0-2c-.363 0-.724.067-1.057.213c-1.21.53-1.724 1.956-1.291 3.173a2.4 2.4 0 0 0 1.291 1.401M15 11c-.363 0-.724.067-1.057.213c-1.21.53-1.724 1.956-1.291 3.173a2.4 2.4 0 0 0 1.291 1.401c.333.146.694.213 1.057.213c.708 0 1.398-.271 1.872-.804A2.56 2.56 0 0 0 17.5 13.5c0-1.429-1.068-2.5-2.5-2.5");
}

</style>
