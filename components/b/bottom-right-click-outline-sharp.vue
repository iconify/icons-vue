<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfrzzdbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bottom-right-click-outline-sharp" /></template>
<style>
.kfrzzdbfa {
  fill: currentColor;
  d: path("M3.98 20v-1H19V4.02h1V20zm9.954-3.934Q13.5 15.633 13.5 15t.434-1.066T15 13.5t1.066.434q.434.433.434 1.066t-.434 1.066q-.433.434-1.066.434t-1.066-.434M6 12v-1h4.292l-6.08-6.1l.688-.689l6.1 6.081V6h1v6z");
}

</style>
