<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfftzc78x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:car-fan-recirculate-sharp" /></template>
<style>
.gfftzc78x {
  fill: currentColor;
  d: path("M6.5 20q-1.025 0-1.875-.537T3.35 18H0v-8h3l2-5.5h10l1.425 2.375L13.95 9.75h-1.575L10 7.375L5.375 12L10 16.625l2.375-2.375h3.65l3.925-4.575L24 10v8h-3.35q-.425.925-1.275 1.463T17.5 20t-1.875-.537T14.35 18h-4.7q-.425.925-1.275 1.463T6.5 20m3.5-5.5l1.05-1.05l-.675-.7h4.95L21.55 5.5l-1.125-1l-5.775 6.75h-4.275l.675-.7L10 9.5L7.5 12z");
}

</style>
