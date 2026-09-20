<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b0p11ofow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:less-than-thin" /></template>
<style>
.b0p11ofow {
  fill: currentColor;
  d: path("M203.61 201.71A4 4 0 0 1 200 204a3.85 3.85 0 0 1-1.71-.39l-152-72a4 4 0 0 1 0-7.23l152-72a4 4 0 0 1 3.42 7.23L57.34 128l144.37 68.38a4 4 0 0 1 1.9 5.33");
}

</style>
