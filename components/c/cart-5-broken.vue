<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qjfpjhbpv"/><path class="ke3a2_b3b"/><path class="s5yx09_gc"/><path class="euua0jb3r"/><path class="pynb684jo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-5-broken" /></template>
<style>
.euua0jb3r {
  stroke-linejoin: round;
  d: path("M18 9L15 3");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ke3a2_b3b {
  stroke-linejoin: round;
  d: path("M16 12H12M9 12H8");
}

.pynb684jo {
  stroke-linejoin: round;
  d: path("M6 9L9 3");
}

.qjfpjhbpv {
  d: path("M20.0159 16.2572C19.5289 18.5297 19.2854 19.666 18.4603 20.333C17.6353 21 16.4732 21 14.1491 21H9.85004C7.5259 21 6.36383 21 5.53876 20.333C4.71369 19.666 4.4702 18.5297 3.98323 16.2572L3.55466 14.2572C2.83619 10.9043 2.47696 9.22793 3.37751 8.11397C4.27806 7 5.99253 7 9.42147 7H14.5776C18.0066 7 19.721 7 20.6216 8.11397C21.2924 8.94376 21.2642 10.0856 20.9092 12");
}

.s5yx09_gc {
  stroke-linejoin: round;
  d: path("M10 15H14");
}

</style>
