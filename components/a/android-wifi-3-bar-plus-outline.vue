<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8ro_pbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:android-wifi-3-bar-plus-outline" /></template>
<style>
.b8ro_pbfr {
  fill: currentColor;
  d: path("M18.039 19v-2h-2v-1h2v-2h1v2h2v1h-2v2zM3.185 10.475L1.774 9.062q2.089-1.956 4.721-3.009T12 5t5.506 1.053t4.721 3.009l-1.413 1.413q-1.798-1.684-4.073-2.58T12 7t-4.74.895t-4.073 2.58m7.747 8.091q-.434-.433-.434-1.066t.434-1.066Q11.367 16 12 16t1.066.434t.434 1.066t-.434 1.066Q12.633 19 12 19t-1.066-.434M7.2 14.45l-1.408-1.408q1.264-1.22 2.861-1.872q1.597-.65 3.347-.65q1.316 0 2.538.37q1.221.371 2.302 1.064q-.534.182-1.018.498q-.484.315-.866.735q-.693-.331-1.438-.5T12 12.52q-1.367 0-2.597.5T7.2 14.45");
}

</style>
