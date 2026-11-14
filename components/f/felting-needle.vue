<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkuv9l_es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:felting-needle" /></template>
<style>
.gkuv9l_es {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.791 12.748l7.783-9.266q.048-.056.083-.121t.058-.135q.022-.071.03-.144t.002-.147t-.027-.144t-.055-.137t-.08-.123q-.046-.058-.103-.105q-.114-.096-.256-.141t-.291-.032t-.281.082t-.228.183l-8.1 9.642q-.401-.077-.856-.097q-2.78-.121-3.87 1.961q-2.336-.763-4.114 1.371q-1.974 2.369-.675 5.4q.043.102.114.186q.07.085.162.145q.092.061.197.092q.106.032.216.032H15q1.322 0 1.981-1.161q.516-.911.39-2.164q-.276-2.762-2.244-3.121q-.347-1.369-1.336-2.056");
}

</style>
