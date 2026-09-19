<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f_re03ygq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bankid-no" /></template>
<style>
.f_re03ygq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-27 10.6h5.1m-5.1 15.8h5.1m-5.1-5.3h5.1m4.8-5.2h5.2m-5.2 5.2h5.2m4.8-10.5h5.1m-5.1 5.3h5.1m-5.1 10.5h5.1");
}

</style>
