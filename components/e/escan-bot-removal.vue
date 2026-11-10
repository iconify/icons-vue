<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ot_pn16ip"/><path class="ri37bhb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:escan-bot-removal" /></template>
<style>
.ot_pn16ip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.942 28.38l4.948 7.209c-4.758 7.158-14.36 9.065-21.448 4.26s-8.976-14.502-4.219-21.66s14.36-9.065 21.449-4.26a15.5 15.5 0 0 1 4.585 4.839L23.664 32.504q7.973 2.748 13.278-4.124");
}

.ri37bhb2g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.303 18.768l-9.286 6.873q2.647-6.873 9.286-6.873m-16.597 2.067l.672-7.556l-2.658 2.75c-1.334-1.375-.662-3.096.662-5.153l1.996-3.085L10.386 5.5l-3.32 6.405c-1.323 3.431-.661 6.18 1.335 7.555l-2.658 2.75z");
}

</style>
