<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1g9bccjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:e911-avatar-outline-sharp" /></template>
<style>
.k1g9bccjc {
  fill: currentColor;
  d: path("M16 11V9h2v2zm0-4V2h2v5zm3.95 14q-3.125 0-6.187-1.35T8.2 15.8t-3.85-5.55T3 4.05V3h5.9l.925 5.025l-2.85 2.875q.55.975 1.225 1.85t1.45 1.625q.725.725 1.588 1.388T13.1 17l2.9-2.9l5 1.025V21zM6.025 9l1.65-1.65L7.25 5H5.025q.125 1.125.375 2.113T6.025 9m8.95 8.95q1 .425 2.013.675T19 18.95v-2.2l-2.35-.475zm0 0");
}

</style>
