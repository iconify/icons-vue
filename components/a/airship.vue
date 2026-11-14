<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyznrraxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:airship" /></template>
<style>
.xyznrraxx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.638 6.154q-.309.164-.585.336L3.086 4.031q-.094-.116-.224-.188q-.131-.072-.279-.088q-.148-.017-.292.025q-.143.041-.26.134q-.116.094-.188.224q-.072.131-.088.279q-.017.148.025.292q.041.143.134.26l1.959 2.448Q2.749 8.555 2.75 10q-.001 1.445 1.123 2.583l-1.959 2.448q-.093.117-.134.26t-.025.292q.016.148.088.279q.072.13.188.224q.058.046.124.08q.065.034.136.054q.071.021.145.027q.073.007.147-.002q.073-.008.144-.03t.135-.058t.121-.083t.103-.105l1.967-2.459q.276.172.585.336q1.613.854 3.617 1.19q-.005.104-.005.214q0 2.5 2.5 2.5h1.5q1.036 0 1.768-.732t.732-1.768q0-.213-.031-.414q1.432-.348 2.643-.99q2.89-1.53 2.888-3.846q.002-2.316-2.888-3.846Q15.708 4.748 12 4.748T5.638 6.154");
}

</style>
