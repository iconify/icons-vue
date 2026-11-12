<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rsrhfac5n"/><path class="h15dvobst"/><path class="ol4qk2w7f"/><path class="ll6i-b9su"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-off-broken" /></template>
<style>
.h15dvobst {
  d: path("M3.29916 20.7008C3 19.8314 3 18.3867 3 16.0909V11.0975");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ll6i-b9su {
  d: path("M5.49902 21.9565C6.39205 21.7436 7.5139 20.7513 9.44213 19.0458L9.44214 19.0458C10.4612 18.1445 10.9707 17.6938 11.5603 17.575C11.8506 17.5166 12.1494 17.5166 12.4397 17.575C13.0292 17.6938 13.5388 18.1445 14.5578 19.0458L14.5579 19.0458C16.8633 21.0849 18.016 22.1045 19.0031 21.9915C19.4738 21.9376 19.9158 21.7349 20.2659 21.4123C21 20.7357 21 19.1875 21 16.0909V11.0975C21 9.2102 21 7.73817 20.8877 6.56787");
}

.ol4qk2w7f {
  d: path("M20.1209 3.87889C19.9938 3.68194 19.8483 3.50064 19.6818 3.3323C18.3638 2 16.2425 2 11.9998 2C7.75718 2 5.63586 2 4.31784 3.3323C3.50761 4.15131 3.19546 5.27717 3.0752 7.01938");
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

</style>
