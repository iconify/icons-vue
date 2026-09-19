<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b3bv_-3rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:castbox" /></template>
<style>
.b3bv_-3rl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.115 3L6.019 13.791v20.522L24.115 45l17.866-10.687V13.791zM13.394 21.243v5.514zm.023 2.748h4.93zm9.695-7.452V28.25zm4.678 1.083V28.35zm-9.42 1.222v12.618zm.029 3.243h4.63zm4.798 1.126h4.534zm14.263-.801v3.176m-5.006-5.07v6.964");
}

</style>
