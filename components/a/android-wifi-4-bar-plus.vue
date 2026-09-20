<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9hxiwo8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:android-wifi-4-bar-plus" /></template>
<style>
.t9hxiwo8y {
  fill: currentColor;
  d: path("M2.094 10.177L1.012 9.133Q3.302 7.11 6.13 6.055T12 5t5.87 1.045q2.828 1.046 5.118 3.088l-1.082 1.044q-2.05-1.802-4.598-2.749T12 6.481t-5.308.947t-4.598 2.749m8.82 8.428q-.452-.453-.452-1.086t.453-1.076T12 16t1.086.443t.452 1.076t-.453 1.086q-.452.453-1.085.453t-1.086-.453M7.567 15.41l-1.058-1.064q1.16-.969 2.573-1.475T12 12.366q.825 0 1.62.15q.794.151 1.551.453q-.294.26-.527.58t-.411.67q-.537-.186-1.089-.27q-.552-.083-1.144-.083q-1.217 0-2.351.392T7.566 15.41m-2.724-2.614l-1.057-1.044Q5.5 10.246 7.618 9.469t4.406-.777t4.393.765t3.823 2.27l-.133.139q-.375-.125-.76-.188q-.385-.062-.81-.062q-.234 0-.45.011t-.44.067q-1.275-.742-2.699-1.132t-2.93-.389q-1.979 0-3.828.667q-1.849.666-3.349 1.956M18.04 19v-2h-2v-1h2v-2h1v2h2v1h-2v2z");
}

</style>
