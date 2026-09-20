<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7oueoqow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:emergency-recording-sharp" /></template>
<style>
.o7oueoqow {
  fill: currentColor;
  d: path("M9 17h2v-3.275l3 1.725l1-1.725L12 12l3-1.725l-1-1.725l-3 1.725V7H9v3.275L6 8.55l-1 1.725L8 12l-3 1.725l1 1.725l3-1.725zm-7 3V4h16v6.5l4-4v11l-4-4V20z");
}

</style>
