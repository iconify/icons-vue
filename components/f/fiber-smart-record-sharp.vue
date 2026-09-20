<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swyx6siiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fiber-smart-record-sharp" /></template>
<style>
.swyx6siiw {
  fill: currentColor;
  d: path("M9 19q-2.925 0-4.962-2.037T2 12t2.038-4.962T9 5t4.963 2.038T16 12t-2.037 4.963T9 19m7-.1v-2q1.75-.35 2.875-1.725T20 12t-1.125-3.175T16 7.1v-2q2.6.35 4.3 2.312T22 12t-1.7 4.588T16 18.9");
}

</style>
