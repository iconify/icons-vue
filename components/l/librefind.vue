<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kj5d3_k3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:librefind" /></template>
<style>
.kj5d3_k3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6 5.967l36 36.066m-4.112-20.359c4.575 4.864 3.824 11.615-1.646 14.59M16.72 26.258c-.123 7.451 3.649 11.92 11.46 11.596M7.146 16.686c-.917 4.872.66 7.04 3.303 9.235m.67-14.826c9.643-1.9 14.444-1.3 17.67 2.08c3.997 4.185 3.613 10.774-2.246 13.372");
}

</style>
