<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v35ne3b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chess-knight-sharp" /></template>
<style>
.v35ne3b2j {
  fill: currentColor;
  d: path("M5 22v-5.225l6-3.025V12l-3.475 1.725q-.3.15-.625.225t-.65.075q-.775 0-1.463-.4t-1.062-1.15q-.35-.675-.3-1.437T3.9 9.625L7 5L5 2h6q3.325 0 5.663 2.325T19 10v12z");
}

</style>
