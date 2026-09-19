<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_dlo7bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-maps-ugc" /></template>
<style>
.t_dlo7bnn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2C6.48 2 2 6.48 2 12c0 1.54.36 2.98.97 4.29L1 23l6.71-1.97c1.31.61 2.75.97 4.29.97c5.52 0 10-4.48 10-10S17.52 2 12 2m4 11h-3v3h-2v-3H8v-2h3V8h2v3h3z");
}

</style>
