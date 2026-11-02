<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkda8yb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-alt-fill-sharp" /></template>
<style>
.qkda8yb0d {
  fill: currentColor;
  d: path("M2 5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm7.943 10.787c.333.146.694.213 1.057.213a1 1 0 0 0 0-2c-.324 0-.5-.175-.5-.5s.176-.5.5-.5a1 1 0 0 0 0-2c-.363 0-.724.067-1.057.213c-1.21.53-1.724 1.956-1.291 3.173a2.4 2.4 0 0 0 1.291 1.401M15 11c-.363 0-.724.067-1.057.213c-1.21.53-1.724 1.956-1.291 3.173a2.4 2.4 0 0 0 1.291 1.401c.333.146.694.213 1.057.213c.708 0 1.398-.271 1.872-.804A2.56 2.56 0 0 0 17.5 13.5c0-1.429-1.068-2.5-2.5-2.5");
}

</style>
