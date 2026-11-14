<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iszryo-3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gfci-outlet" /></template>
<style>
.iszryo-3z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.875 1.75h6.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-6.25q-2.123 0-3.624-1.501T3.75 17.125V6.875q0-2.123 1.501-3.624T8.875 1.75M9.75 10h-1q-2 0-2 2t2 2h1q2 0 2-2t-2-2m4.5 0q-2 0-2 2t2 2h1q2 0 2-2t-2-2z");
}

</style>
