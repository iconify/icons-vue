<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mee2u3bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-stick-l3-outline-rounded" /></template>
<style>
.mee2u3bce {
  fill: currentColor;
  d: path("M12 5.442L10 2.77h4zm5.675 9.622Q20 13.86 20 12.136T17.675 9.2T12 7.985T6.325 9.199T4 12.136t2.325 2.928Q8.65 16.267 12 16.267t5.675-1.203m-1.406 1.594v2.746q0 .666-.474 1.14t-1.141.475H9.327q-.667 0-1.141-.474t-.475-1.141v-2.746q-2.12-.666-3.416-1.851T3 12.133Q3 9.99 5.62 8.486t6.376-1.505t6.38 1.505T21 12.133q0 1.488-1.295 2.674t-3.436 1.85m-5.071-1.984h2.198q.166 0 .27-.103q.103-.103.103-.267t-.104-.27t-.269-.106h-1.833V9.942q0-.153-.111-.269q-.111-.115-.273-.115t-.273.115t-.112.27v4.326q0 .162.122.283q.12.121.282.121");
}

</style>
