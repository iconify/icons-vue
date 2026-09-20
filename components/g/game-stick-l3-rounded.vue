<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_4zk7bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-stick-l3-rounded" /></template>
<style>
.e_4zk7bic {
  fill: currentColor;
  d: path("M12 5.442L10 2.77h4zm4.27 11.216v2.746q0 .666-.475 1.14t-1.141.475H9.327q-.667 0-1.141-.474t-.475-1.141v-2.746q-2.12-.666-3.416-1.851T3 12.133Q3 9.99 5.62 8.486t6.376-1.505t6.38 1.505T21 12.133q0 1.488-1.295 2.674t-3.436 1.85m-5.071-1.984h2.198q.166 0 .27-.103q.103-.103.103-.267t-.104-.27t-.269-.106h-1.833V9.942q0-.153-.111-.269q-.111-.115-.273-.115t-.273.115t-.112.27v4.326q0 .162.122.283q.12.121.282.121");
}

</style>
