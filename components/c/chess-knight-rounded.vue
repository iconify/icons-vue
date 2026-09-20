<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-vbhv50t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chess-knight-rounded" /></template>
<style>
.q-vbhv50t {
  fill: currentColor;
  d: path("M7.5 21.02q-.69 0-1.153-.475q-.463-.474-.463-1.139v-1.613q0-.464.233-.84t.637-.593l4.669-2.418V11.29l-3.821 1.955q-.223.131-.471.187t-.497.056q-.62 0-1.145-.323t-.822-.9q-.273-.541-.234-1.141q.04-.601.37-1.113l3.005-4.625l-.749-1.15q-.269-.396-.032-.816T7.74 3H11q2.894 0 4.928 2.075t2.033 5.04v9.289q0 .666-.474 1.14t-1.14.475z");
}

</style>
