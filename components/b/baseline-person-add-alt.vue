<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rseaj69xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-person-add-alt" /></template>
<style>
.rseaj69xh {
  fill: currentColor;
  d: path("M13 8c0-2.21-1.79-4-4-4S5 5.79 5 8s1.79 4 4 4s4-1.79 4-4m-2 0c0 1.1-.9 2-2 2s-2-.9-2-2s.9-2 2-2s2 .9 2 2M1 18v2h16v-2c0-2.66-5.33-4-8-4s-8 1.34-8 4m2 0c.2-.71 3.3-2 6-2c2.69 0 5.78 1.28 6 2zm17-3v-3h3v-2h-3V7h-2v3h-3v2h3v3z");
}

</style>
