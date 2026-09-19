<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="db-8o_b0z"/><path class="cbybbccbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:animewatch" /></template>
<style>
.cbybbccbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.056 20.486c0 6.16-3.777 10.84-6.269 13.258l-6.27-9.66h-3.035l-6.27 9.66c-2.494-2.42-6.268-7.1-6.268-13.258H4.5c0 12.056 10.332 19.276 10.772 19.578l2.302 1.579l6.425-9.898l6.426 9.898l2.302-1.58c.44-.3 10.773-7.521 10.773-19.577z");
}

.db-8o_b0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 17.662c4.182 0 7.824 2.277 9.78 5.653a11.24 11.24 0 0 0 1.525-5.653c0-6.243-5.062-11.305-11.305-11.305S12.695 11.42 12.695 17.662c0 2.062.56 3.988 1.525 5.653c1.955-3.376 5.598-5.653 9.78-5.653");
}

</style>
