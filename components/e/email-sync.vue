<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="os4esubmw"/><path class="s3a5wbbwq"/><path class="b1csntfxh"/><path class="opjjxbd2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:email-sync" /></template>
<style>
.b1csntfxh {
  d: path("M20.75 14.5v2h-2M21 18a3 3 0 0 1-5.5 1.5");
}

.opjjxbd2k {
  d: path("M15.25 21.5v-2h2");
}

.os4esubmw {
  d: path("M12 18.5H2.5v-13h19v6.2");
}

.s3a5wbbwq {
  d: path("m2.5 7l9.5 6l9.5-6M15 18a3 3 0 0 1 5.5-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
