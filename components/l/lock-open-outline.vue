<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb7pzjj_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lock-open-outline" /></template>
<style>
.cb7pzjj_o {
  fill: currentColor;
  d: path("M6.616 9H15V7q0-1.25-.875-2.125T12 4t-2.125.875T9 7H8q0-1.671 1.165-2.835Q10.329 3 12 3t2.836 1.165T16 7v2h1.385q.67 0 1.143.472q.472.472.472 1.144v8.769q0 .67-.472 1.143q-.472.472-1.143.472H6.615q-.67 0-1.143-.472Q5 20.056 5 19.385v-8.77q0-.67.472-1.143Q5.944 9 6.616 9m0 11h10.769q.269 0 .442-.173t.173-.442v-8.77q0-.269-.173-.442T17.385 10H6.615q-.269 0-.442.173T6 10.616v8.769q0 .269.173.442t.443.173m6.45-3.934q.434-.433.434-1.066t-.434-1.066T12 13.5t-1.066.434Q10.5 14.367 10.5 15t.434 1.066q.433.434 1.066.434t1.066-.434M6 20V10z");
}

</style>
