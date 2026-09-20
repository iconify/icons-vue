<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyfeauvok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:earbud-left-outline-rounded" /></template>
<style>
.cyfeauvok {
  fill: currentColor;
  d: path("M8.404 21q-.69 0-1.153-.462t-.462-1.153v-7.712H5.615q-.69 0-1.153-.462T4 10.058V6.616q0-.691.463-1.153T5.616 5h8.692v1H5.616q-.27 0-.443.173T5 6.616v3.442q0 .269.173.442t.443.173H6.98q.343 0 .575.232t.233.576v7.904q0 .269.173.442t.442.173h1.538q.27 0 .443-.173t.173-.443v-7.903q0-.343.232-.576t.576-.232h2.942v1h-2.75v7.712q0 .69-.463 1.152T9.942 21zm10.173-8.913q-1.423 1.586-3.538 1.586q-.311 0-.521-.21t-.21-.52V3.73q0-.31.21-.521q.21-.21.52-.21q2.116 0 3.539 1.577T20 8.327t-1.423 3.76m-.604-6.739q-1.027-1.277-2.665-1.357v8.692q1.638-.1 2.665-1.377T19 8.327t-1.027-2.979m-2.665 2.979");
}

</style>
