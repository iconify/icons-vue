<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng_y0bnwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:attach-file-rounded" /></template>
<style>
.ng_y0bnwm {
  fill: currentColor;
  d: path("M17.346 15.539q0 2.271-1.565 3.866T11.952 21t-3.838-1.595t-1.576-3.867v-8.73q0-1.587 1.092-2.697Q8.72 3 10.308 3t2.678 1.11t1.091 2.698v8.269q0 .88-.615 1.517q-.614.637-1.498.637t-1.52-.627t-.636-1.527V7.269q0-.212.144-.356q.143-.144.356-.144t.356.144t.144.356v7.808q0 .479.327.816q.328.338.807.338t.807-.338t.328-.816V6.789q-.006-1.166-.805-1.977T10.309 4t-1.967.821t-.804 1.987v8.73q-.005 1.853 1.283 3.157Q10.11 20 11.96 20q1.823 0 3.1-1.305t1.287-3.156v-8.27q0-.212.144-.356t.357-.144t.356.144t.143.356z");
}

</style>
