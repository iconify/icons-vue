<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n2gum0idi"/><path class="e0g1lp8aq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:elevation-profile-sharp" /></template>
<style>
.e0g1lp8aq {
  d: path("m7.12 16.82l2.51-6.39l.37-.93l.62.78l1.76 2.19l.62.78l.42-.91l2.66-5.68l.42-.91l.33.94l3.59 10.12l.33.94h-14z");
}

.n2gum0idi {
  d: path("M3.25 2.75v18.5h18");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
