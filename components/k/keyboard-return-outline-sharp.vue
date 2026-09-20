<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjxbi-ojd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-return-outline-sharp" /></template>
<style>
.hjxbi-ojd {
  fill: currentColor;
  d: path("m9 18l-6-6l6-6l1.4 1.4L6.8 11H19V7h2v6H6.8l3.6 3.6z");
}

</style>
