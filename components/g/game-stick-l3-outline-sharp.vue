<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj7kj1q4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-stick-l3-outline-sharp" /></template>
<style>
.dj7kj1q4c {
  fill: currentColor;
  d: path("M12 5.442L10 2.77h4zm5.675 9.622Q20 13.86 20 12.136T17.675 9.2T12 7.985T6.325 9.199T4 12.136t2.325 2.928Q8.65 16.267 12 16.267t5.675-1.203m-1.406 1.594v4.361H7.712v-4.361q-2.121-.666-3.417-1.851T3 12.133Q3 9.99 5.62 8.486t6.376-1.505t6.38 1.505T21 12.133q0 1.488-1.295 2.674t-3.436 1.85m-5.475-1.984h2.975v-.746h-2.206v-4.37h-.769z");
}

</style>
