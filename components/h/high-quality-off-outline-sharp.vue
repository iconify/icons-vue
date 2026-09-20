<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apllqu2gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:high-quality-off-outline-sharp" /></template>
<style>
.apllqu2gn {
  fill: currentColor;
  d: path("m17.385 14.727l-.885-.885v-3.65h-2.615v1.035L13 10.361V9.308h4.385zm-10.77-.035V9.308H7.5v2.5h2.616v-1.5l.884.884v3.5h-.885v-2H7.5v2zm12.897 6.427L17.38 19H3V5h1.808l1 1H4v12h12.38L2.363 3.97l.707-.708l17.15 17.15zM21 18.342l-1-1V6H8.658l-1-1H21zm-10.521-6.244");
}

</style>
