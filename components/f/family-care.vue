<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nscmu5hgh"/><path class="i7m1e_5cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:family-care" /></template>
<style>
.i7m1e_5cs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.15 30.63c2.63-1.343 7.139-1.307 9.637 1.18c2.615 2.601 2.245 5.407.538 7.44c-1.38 1.645-6.193 2.643-8.43 2.543m7.565-19.678a5.093 5.093 0 0 1-10.188 0a5.094 5.094 0 0 1 10.189 0");
}

.nscmu5hgh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.906 13.509a8.01 8.01 0 0 1-8.01 8.009a8.01 8.01 0 0 1-8.012-8.008v-.001a8.01 8.01 0 0 1 8.01-8.009a8.01 8.01 0 0 1 8.012 8.009m5.779 27.433c-.03.683-.788.931-1.754 1.066c-6.283.872-17.42.6-20.44-.937c-5.42-2.758-5.183-8.318-1.423-12.62c3.47-3.968 8.66-5.066 13.42-4.095c4.61.942 10.578 7.85 10.197 16.586");
}

</style>
