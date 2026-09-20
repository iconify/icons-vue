<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_zwsrmqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:heat-pump-balance" /></template>
<style>
.r_zwsrmqg {
  fill: currentColor;
  d: path("M8.77 16.792q.73-.73.73-1.769v-4.77q0-.616.441-1.058q.442-.441 1.059-.441t1.059.441t.441 1.059v4.769q0 1.039.73 1.77t1.77.73t1.77-.73t.73-1.77v-5.77q0-.616.441-1.058q.442-.441 1.059-.441h2.406l-1.694 1.65l.688.713l2.889-2.863L20.4 4.366l-.688.713l1.675 1.675H19q-1.038 0-1.77.73q-.73.732-.73 1.77v5.769q0 .618-.441 1.059q-.442.441-1.059.441t-1.059-.441t-.441-1.059v-4.77q0-1.037-.73-1.768q-.731-.731-1.77-.731t-1.77.73q-.73.732-.73 1.77v4.769q0 .618-.441 1.059q-.442.441-1.059.441t-1.059-.441Q5.5 15.64 5.5 15.023v-7.27h-1v7.27q0 1.039.73 1.77t1.77.73t1.77-.73M3.615 20.6q-.672 0-1.144-.472T2 18.985v-6.846h20v6.846q0 .67-.472 1.143q-.472.472-1.143.472z");
}

</style>
