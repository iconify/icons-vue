<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzq0nybrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:circle-of-fifths" /></template>
<style>
.pzq0nybrk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75Q9.75 1.75 9.75 4T12 6.25T14.25 4T12 1.75m0 3q-.75 0-.75-.75t.75-.75t.75.75t-.75.75m.5-.75q0 .5-.5.5t-.5-.5t.5-.5t.5.5m-4 0v-.049q-1.464.639-2.687 1.862T3.951 8.5H4q3.5 0 3.5 3.5T4 15.5h-.049q.639 1.464 1.862 2.687T8.5 20.049V20q0-3.5 3.5-3.5t3.5 3.5v.049q1.464-.639 2.687-1.862t1.862-2.687H20q-3.5 0-3.5-3.5T20 8.5h.049q-.639-1.464-1.862-2.687T15.5 3.951V4q0 3.5-3.5 3.5T8.5 4m5.091 5.031l1.378 1.378q.66.659.66 1.591t-.66 1.591l-1.378 1.378q-.659.66-1.591.66t-1.591-.66l-1.378-1.378q-.66-.659-.66-1.591t.66-1.591l1.378-1.378q.659-.66 1.591-.66t1.591.66M1.75 12q0-2.25 2.25-2.25T6.25 12T4 14.25T1.75 12m16 0q0-2.25 2.25-2.25T22.25 12T20 14.25T17.75 12m-14.5 0q0 .75.75.75t.75-.75t-.75-.75t-.75.75m16 0q0 .75.75.75t.75-.75t-.75-.75t-.75.75M4 11.5q.5 0 .5.5t-.5.5t-.5-.5t.5-.5m16 0q.5 0 .5.5t-.5.5t-.5-.5t.5-.5m-8 6.25q-2.25 0-2.25 2.25T12 22.25T14.25 20T12 17.75m0 3q-.75 0-.75-.75t.75-.75t.75.75t-.75.75m.5-.75q0 .5-.5.5t-.5-.5t.5-.5t.5.5");
}

</style>
