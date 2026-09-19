<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="k5i_pccsq"/><path class="wt9dj4boi"/><path class="vbg_2wgbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eboo" /></template>
<style>
.k5i_pccsq {
  d: path("M23.257 19.773c0 4.731-4.198 8.567-9.376 8.568c-5.179.001-9.378-3.832-9.381-8.564c-.003-4.73 4.192-8.569 9.37-8.573c5.179-.004 9.38 3.828 9.386 8.56z");
}

.vbg_2wgbd {
  d: path("M30.44 19.749c0 2.149 1.68 3.89 3.753 3.891s3.754-1.74 3.755-3.89c.001-2.148-1.678-3.892-3.75-3.893s-3.755 1.738-3.757 3.887zm-6.416 17.047l6.31-6.364H17.725z");
}

.wt9dj4boi {
  d: path("M17.56 19.749c0 2.149-1.68 3.89-3.753 3.891s-3.754-1.74-3.755-3.89s1.678-3.892 3.75-3.893s3.755 1.738 3.757 3.887zm7.184.024c0 4.731 4.197 8.567 9.375 8.568c5.179.001 9.378-3.832 9.381-8.564c.003-4.73-4.192-8.569-9.37-8.573c-5.179-.004-9.38 3.828-9.387 8.56z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
