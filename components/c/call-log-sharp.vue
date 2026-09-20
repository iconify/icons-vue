<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0rcazbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:call-log-sharp" /></template>
<style>
.c0rcazbtu {
  fill: currentColor;
  d: path("M18.95 22q-3.125 0-6.187-1.35T7.2 16.8t-3.85-5.55T2 5.05V4h5.9l.925 5.025l-2.85 2.875q.55.975 1.225 1.85t1.45 1.625q.725.725 1.588 1.388T12.1 18l2.9-2.9l5 1.025V22zM12 4V2h10v2zm0 4V6h10v2zm0 4v-2h10v2z");
}

</style>
