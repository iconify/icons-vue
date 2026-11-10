<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d7fe47xim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:idv" /></template>
<style>
.d7fe47xim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.248 9.039v8.419m18.715 0v-8.42h1.894a3.683 3.683 0 0 1 3.684 3.684v1.052a3.683 3.683 0 0 1-3.684 3.684zM16.036 30.542l-2.789 8.42l-2.788-8.42M5.5 24h15.496m6.008 0H42.5M24 5.5v15.496m0 6.008V42.5");
}

</style>
