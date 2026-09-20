<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcsqxfv6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:humidity-mid-outline-rounded" /></template>
<style>
.rcsqxfv6x {
  fill: currentColor;
  d: path("M12 20.5q-2.91 0-4.955-2.006T5 13.61q0-1.373.555-2.628t1.487-2.24L12 3.884l4.958 4.858q.933.985 1.487 2.24T19 13.615q0 2.882-2.045 4.884T12 20.5m-6-6.88h12q0-1.176-.45-2.245T16.25 9.5L12 5.3L7.75 9.5q-.85.805-1.3 1.875T6 13.619");
}

</style>
