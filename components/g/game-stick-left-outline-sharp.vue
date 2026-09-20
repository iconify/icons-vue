<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tccclfb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-stick-left-outline-sharp" /></template>
<style>
.tccclfb9x {
  fill: currentColor;
  d: path("M17.675 13.06Q20 11.86 20 10.137T17.675 7.2T12 5.984T6.325 7.2T4 10.136t2.325 2.924T12 14.262t5.675-1.2m-1.406 1.597v4.361H7.712v-4.361q-2.121-.666-3.417-1.851T3 10.133Q3 7.99 5.62 6.486t6.376-1.505t6.38 1.505T21 10.133q0 1.488-1.295 2.674t-3.436 1.85m-5.475-1.984h2.975v-.746h-2.206v-4.37h-.769z");
}

</style>
