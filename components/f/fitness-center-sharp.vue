<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0l9ohp-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fitness-center-sharp" /></template>
<style>
.x0l9ohp-c {
  fill: currentColor;
  d: path("m13.592 21.4l-.9-.9l3.55-3.55L7.05 7.758l-3.55 3.55l-.9-.9l1.439-1.45l-.9-.9l2.1-2.1l-1.4-1.412l.707-.707l1.412 1.4l2.1-2.1l.9.9l1.45-1.439l.9.9l-3.55 3.55l9.192 9.192l3.55-3.55l.9.9l-1.438 1.45l.9.9l-2.1 2.1l1.4 1.412l-.708.708l-1.412-1.4l-2.1 2.1l-.9-.9z");
}

</style>
