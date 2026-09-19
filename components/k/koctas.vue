<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wjqwzhbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:koctas" /></template>
<style>
.wjqwzhbrg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 38.826h-29V18.553L24 7.575l14.5 10.978zM24 19.769L9.5 30.747m9.988-7.561v15.64m0-9.331H38.5m-9.988 0V10.991m0 12.195l-12.566-9.514");
}

</style>
