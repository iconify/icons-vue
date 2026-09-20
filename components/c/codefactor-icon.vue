<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":259};
const content = `<defs><linearGradient id="SVGaUJX2d1X" x1="-.002%" x2="100.002%" y1="49.998%" y2="49.998%"><stop offset="0%" class="h3_lujbvp"/><stop offset="100%" class="s_le3pbns"/></linearGradient></defs><path class="noxgf2brl"/><path fill="url(#SVGaUJX2d1X)" class="dmgv1sjvh"/><path fill="url(#SVGaUJX2d1X)" class="tair10b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:codefactor-icon" /></template>
<style>
.dmgv1sjvh {
  d: path("M120.576 0C104.956 0 92.29 12.786 92.29 28.573c0 15.786 12.667 28.572 28.286 28.572h107.148c15.62 0 28.275-12.786 28.275-28.572C255.999 12.786 243.343 0 227.712 0H120.564z");
}

.h3_lujbvp {
  stop-color: var(--svg-color--0aa1a5, #0aa1a5);
}

.noxgf2brl {
  fill: var(--svg-color--f44a6a, #f44a6a);
  d: path("M56.586 28.573c0 15.786-12.668 28.572-28.287 28.572C12.667 57.145 0 44.36 0 28.573S12.667 0 28.299 0c15.62 0 28.287 12.786 28.287 28.573m0 100.742c0 15.774-12.668 28.572-28.287 28.572C12.667 157.887 0 145.09 0 129.315c0-15.787 12.667-28.573 28.299-28.573c15.62 0 28.287 12.786 28.287 28.573m0 100.73c0 15.787-12.668 28.573-28.287 28.573C12.667 258.618 0 245.832 0 230.045c0-15.786 12.667-28.572 28.299-28.572c15.62 0 28.287 12.786 28.287 28.572");
}

.s_le3pbns {
  stop-color: var(--svg-color--50d690, #50d690);
}

.tair10b7n {
  d: path("M120.576 100.73c-15.62 0-28.286 12.798-28.286 28.573c0 15.786 12.667 28.584 28.286 28.584h61.17c15.62 0 28.286-12.798 28.286-28.572c0-15.787-12.667-28.573-28.286-28.573h-61.17z");
}

</style>
