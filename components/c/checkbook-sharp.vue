<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wddddob_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:checkbook-sharp" /></template>
<style>
.wddddob_i {
  fill: currentColor;
  d: path("M2 19V5h20v3h-2l-5 5H6v2h7l-4 4zm4-8h6V9H6zm7 10v-1.75l6.65-6.65l1.75 1.75L14.75 21zm9-7.25L20.25 12l.9-.9q.125-.125.275-.125t.275.125l1.2 1.2q.125.125.125.275t-.125.275z");
}

</style>
