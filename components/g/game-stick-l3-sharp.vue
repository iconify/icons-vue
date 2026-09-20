<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhxhc1b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-stick-l3-sharp" /></template>
<style>
.vhxhc1b-q {
  fill: currentColor;
  d: path("M12 5.442L10 2.77h4zm4.27 11.216v4.361H7.711v-4.361q-2.121-.666-3.417-1.851T3 12.133q0-2.14 2.624-3.646T12 6.98t6.376 1.506T21 12.133q0 1.488-1.295 2.674t-3.436 1.85m-5.475-1.984h2.975v-.746h-2.206v-4.37h-.769z");
}

</style>
