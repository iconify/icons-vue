<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o-ea71vus"/><circle class="luuff9opp"/><circle class="cl3p4cbjw"/><circle class="biiwzjpbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:face-with-open-mouth" /></template>
<style>
.biiwzjpbs {
  cx: 42.75px;
  cy: 25.045px;
  r: 4.5px;
  fill: currentColor;
}

.cl3p4cbjw {
  cx: 20.248px;
  cy: 25.045px;
  r: 4.5px;
  fill: currentColor;
}

.luuff9opp {
  cx: 32px;
  cy: 45.139px;
  r: 7px;
  fill: currentColor;
}

.o-ea71vus {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 57.5C16.836 59.5 4.5 47.164 4.5 32S16.836 4.5 32 4.5S59.5 16.836 59.5 32S47.164 59.5 32 59.5");
}

</style>
