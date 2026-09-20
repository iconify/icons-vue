<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efamp0ygw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:female-outline-sharp" /></template>
<style>
.efamp0ygw {
  fill: currentColor;
  d: path("M11.5 20.5v-2h-2v-1h2v-3.023q-1.917-.215-3.209-1.637Q7 11.417 7 9.489q0-2.083 1.459-3.536Q9.917 4.5 12 4.5t3.541 1.453T17 9.489q0 1.928-1.291 3.35q-1.292 1.423-3.209 1.638V17.5h2v1h-2v2zm3.33-8.172Q16 11.155 16 9.497t-1.172-2.828T11.997 5.5T9.169 6.672T8 9.503t1.172 2.828q1.173 1.169 2.831 1.169q1.659 0 2.828-1.172");
}

</style>
